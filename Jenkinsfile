pipeline {
  agent any
  stages {
    stage('plan') {
      steps {
        echo 'i have a plan to work on CICD'
      }
    }

    stage('code') {
      steps {
        echo 'i have a code to work on CICD'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'i have a build to work on CICD'
          }
        }

        stage('test') {
          steps {
            echo 'i have a test  to work on CICD'
          }
        }

        stage('release') {
          steps {
            echo 'i have a release to work on CICD'
          }
        }

        stage('deploy') {
          steps {
            echo 'i have a deploy to work on CICD'
          }
        }

        stage('operate') {
          steps {
            echo 'i have a operate to work on CICD'
          }
        }

      }
    }

  }
}