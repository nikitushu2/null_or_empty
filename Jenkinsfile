pipeline {
  agent any
  
  tools {nodejs "node"}
  
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/kalwar/null_or_empty.git'
        sh 'npm install'
      }
    }
  }
}