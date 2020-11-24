pipeline {
  agent any
  stages {
    stage('Build Stage') {
      parallel {
        stage('Build Stage') {
          steps {
            sh 'echo "Build Stage"'
          }
        }

        stage('Build Step2') {
          steps {
            sleep 2
          }
        }

      }
    }

    stage('Test Stage') {
      steps {
        sh 'echo "Test Stage"'
      }
    }

    stage('Deploy Stage') {
      steps {
        sh 'echo "Deploy Stage"'
      }
    }

  }
}