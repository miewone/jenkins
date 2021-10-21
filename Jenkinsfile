pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        git(url: 'https://github.com/MiewONE/jenkins.git', branch: 'main', credentialsId: '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')
      }
    }

  }
  environment {
    http = 'test1'
  }
}