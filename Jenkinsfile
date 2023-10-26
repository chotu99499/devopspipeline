pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            echo 'development stage'
          }
        }

        stage('test') {
          steps {
            echo 'test stage'
          }
        }

        stage('plugin ') {
          steps {
            echo 'plugin stage'
            echo 'plugin stage'
          }
        }

      }
    }

    stage('QA') {
      steps {
        echo 'QA stage'
      }
    }

    stage('UAT') {
      steps {
        echo 'UAT stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy stage'
      }
    }

    stage('Operate') {
      steps {
        echo 'operate stage'
      }
    }

  }
}