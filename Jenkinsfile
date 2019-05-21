pipeline {
  agent any
  stages {
    stage('s3 download ') {
      steps {
          withAWS(region:'ap-south-1', credentials:'aws-credentials')\
          {
              s3Download(file: 'PsExec.exe', bucket: 'iqbotsoftware', path: '/home/saurabh')
          }
     
      }
    }
  }
}
