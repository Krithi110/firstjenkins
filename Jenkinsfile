pipeline {
  agent any

  stages {

    stage('Clone') {
      steps {
        git url: 'https://github.com/Krithi110/firstjenkins.git',
          branch: 'main'
      }
    }

    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}        
