pipeline {
  agent any
  stages {
    stage('Deploy Standalone') { 
      steps {
        bat 'mvn deploy -P standalone'
        Dmule.home = 'D:\EsbTools\mule-ee-distribution-standalone-4.2.2\mule-enterprise-standalone-4.2.2'
      }
    }
  }
}
