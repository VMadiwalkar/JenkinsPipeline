pipeline {
  agent any
  stages {
    stage('parallel') {
      parallel {
        steps ('Setp 1') {
          echo 'Step 1 running...'
          timeout 5 > null
        }
        steps ('Setp 2') {
          echo 'Step 2 running...'
          timeout 5 > null
        }
      }
    }
  }
}
