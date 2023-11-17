pipeline{
  agent any
  stages{
    stage('Clone code'){
      steps{
        git url: 'https://github.com/UbaldoFlor/maven-repo.git'
      }
    }
    stage('Build code'){
      steps{
        sh "mvn clean package"
      }
    }
  }
}
