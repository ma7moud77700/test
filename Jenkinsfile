pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello mahmoud'
      }
    }

    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            echo 'test compeleting '
          }
        }

        stage('test2') {
          steps {
            echo 'test2 compeleting'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deployment compeleting'
      }
    }

  }
}