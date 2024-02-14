pipeline {
  agent any
  stages {
    stage('parallel') {
      parallel {
        stage ('Stage 1') {
          steps ('Setp 1') {
            echo "Username: ${USERNAME}" 
          }
        }
        stage ('stage 2') {
          steps ('Setp 2') {
            echo 'Step 2 running...'
          }
        }
      }
    }
  }
}
