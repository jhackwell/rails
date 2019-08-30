pipeline {
  agent {
    docker {
      image 'ruby:2.6.4'
    }

  }
  stages {
    stage('error') {
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