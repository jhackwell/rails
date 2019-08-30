pipeline {
  agent {
    docker {
      image 'ruby:2.1.7'
    }

  }
  stages {
    stage('') {
      agent {
        docker {
          image 'ruby:2.1.7'
        }

      }
      steps {
        sh 'pwd'
      }
    }
  }
  environment {
    STAGE = 'dev'
  }
}