pipeline {
  agent any
  stages{
  tools {nodejs "latest"}
  
    stage('build') {
      steps {
        echo 'Building Javascript project'
        sh 'npm install'
      }
    }
  }
}
