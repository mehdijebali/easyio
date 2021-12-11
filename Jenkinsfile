pipeline {
  agent any
  tools {nodejs "node"}
  stages{
    stage('build') {
      steps {
        echo 'Building Javascript project'
        sh 'npm install'
        sh 'npm run-script build'
      }
    }
  }
}
