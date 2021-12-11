pipeline {
  agent any
  tools {nodejs "node"}
  stages('Install Dependencies'){
    stage{
      steps{
        sh 'npm install'
      }
    }
    stage('build') {
      steps {
        echo 'Building Javascript project'
        sh 'tar czf nanogram.tar.gz node_modules main.js package.json public LICENSE'
      }
    }
  }
}
