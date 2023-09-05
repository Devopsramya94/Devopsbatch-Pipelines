pipeline {
  agent any
  stages {
    stage('Plan') {
      steps {
        echo 'I have a plan to work on cicd'
      }
    }

    stage('code') {
      steps {
        echo 'I have a code to work on cid'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'I have a build to work on cicd'
          }
        }

        stage('Test') {
          steps {
            echo 'I have a test to work on cid'
          }
        }

        stage('Release') {
          steps {
            echo 'I have a release to work on cicd'
          }
        }

        stage('Deploy') {
          steps {
            echo 'I have a deploy to work on cicd'
          }
        }

        stage('Operate') {
          steps {
            echo 'I have a operate to work on cicd'
          }
        }

      }
    }

  }
}