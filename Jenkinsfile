pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''pwd
siteaddress=$(awk \'/LoadBalancer/ {print $4":8080"}\' myfile.txt)'''
      }
    }

  }
}