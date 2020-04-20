pipeline {
  agent any
  tools {
    maven 'M3'
  }
  stages {
     stage('SCM Checkout'){
        git 'https://github.com/javahometech/my-app' }
    stage('Build') {
        sh 'mvn -B -DskipTests clean package'
      }
  }
