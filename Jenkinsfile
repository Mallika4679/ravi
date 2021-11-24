pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "hello,stage1"'
      }
    }

    stage('stage2') {
      steps {
        sh 'echo "hello ,stage2"'
      }
    }

    stage('') {
      steps {
        git(url: 'https://github.com/Mallika4679/ravi.git', branch: 'main', poll: true)
      }
    }

  }
}