node{
   tools {
    maven 'M3'
  }
   stage('SCM Checkout'){
     git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-Package'){  
      sh 'mvn package'
   }
}
