pipeline {
  agent any

  stages {

    stage('Clone') {
      steps {
        git url: 'https://github.com/Adhithya-r2005/simpledemo.git',
          branch: 'main'
      }
    }

    stage('Run Script') {
      steps {
        sh 'chmod +x yooo.sh'
        sh './yooo.sh'
        sh 'chmod +x script.sh'
        sh './script.sh'
        
      }
    }
  }
}
