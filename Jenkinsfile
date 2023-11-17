pipeline {
  agent any
  stages {
    stage('Clone code') {
      steps {
        git(url: 'https://github.com/UbaldoFlor/maven-repo.git', branch: 'main')
      }
    }

    stage('Build code') {
      steps {
        sh 'mvn clean package'
      }
    }

  }
}