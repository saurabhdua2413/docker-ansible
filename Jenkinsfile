pipeline {
  agent any
  stages {
    stage('s3 download ') {
      steps {
    withAWS(credentials:'AKIAIPDUJD7B7ZAWI7WQ')    
        s3Download(bucket: 'iqbotsoftware', file: 'PsExec.exe', path: '/home/saurabh')
      }
    }
  }
}
