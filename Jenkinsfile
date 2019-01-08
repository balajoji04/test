pipeline {
  agent  any {
    dockerfile {
        filename 'dockerfile'
        args '-v /tmp:/tmp'
    }
  }
  stages {
  stage('Notify') {
  steps {
 sh "hostname;ls"
 }
      }
      
  }
 }
