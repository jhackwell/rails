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
          image 'ruby:2.6.4'
        }

      }
      steps {
        sh '''ls -la
'''
      }
    }
  }
  environment {
    STAGE = 'dev'
  }
}