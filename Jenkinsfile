pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/micax3000/jenkins-course', branch: 'main')
      }
    }

    stage('') {
      steps {
        sh '''#!/bin/bash
ls -la'''
      }
    }

  }
}