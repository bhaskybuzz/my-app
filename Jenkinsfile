node{
     stage('SCM Checkout'){
        git 'https://github.com/javahometech/my-app'
     }
    stage('Build'){
     def mvnHome = tool name: 'M2_HOME', type: 'maven'
      sh "${mvnHome}/bin/mvn clean package"
      }
  }
