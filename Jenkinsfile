pipeline {
  agent {
    dockerfile {
        filename 'dockerfile'
        label "docker-nodes"
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
