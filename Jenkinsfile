pipeline {
  agent any
  stages {
    stage {
         parallel {
           step ('Setp 1') {
echo 'Step 1 running...'
timeout 5 > null
}
step ('Setp 2') {
echo 'Step 2 running...'
timeout 5 > null
}
    }
    }
  }
}
