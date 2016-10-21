node {
    parallel (
     phase1: {
         stage('testing backend') {
            sh "echo p1; sleep 10s; echo phase1"
         }
     },
     phase2: {
        stage('testing frontend') {
            sh "echo p2; sleep 5s; echo phase2"
        }
     }
   )
}

node {
    stage('deploying') {
    // some
    }
}
