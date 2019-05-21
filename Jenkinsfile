pipeline {
  agent any
  stages {
    stage('s3 download ') {
      steps {
        s3Download(bucket: 'iqbotsoftware', file: 'PsExec.exe')
      }
    }
  }
}
