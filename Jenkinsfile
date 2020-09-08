pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''pwd
siteaddress=$(sudo awk \'/LoadBalancer/ {print $4":8080"}\' myfile.txt)'''
      }
    }

  }
}