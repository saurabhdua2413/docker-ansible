pipeline {
  agent any
  stages {
    stage('s3 download ') {
      steps {
          withAWS(region:'ap-south-1', credentials:'ebf8c989-90b4-4c42-aabb-16abd0908ab2')\
          {
              s3Download(file: 'PsExec.exe', bucket: 'iqbotsoftware', path: '/home/saurabh')
          }
     
      }
    }
  }
}
