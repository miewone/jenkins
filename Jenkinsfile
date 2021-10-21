pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''#!/bin/bash

sh test.sh'''
      }
    }

  }
  environment {
    http = 'test1'
  }
}