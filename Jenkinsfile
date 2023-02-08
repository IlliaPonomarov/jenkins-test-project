pipeline {
  agent any
  stages {
    stage('checkout Code') {
      steps {
        git(url: 'https://github.com/IlliaPonomarov/jenkins-test-project', branch: 'main')
      }
    }

    stage('') {
      steps {
        sh 'ls -la'
      }
    }

  }
}