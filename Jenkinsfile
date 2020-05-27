pipeline {
  agent any
  stages {
    stage('pull from git') {
      steps {
        git(url: 'https://github.com/t5721654/test.git', branch: 'master')
      }
    }

    stage('print') {
      steps {
        echo 'finish'
      }
    }

  }
}