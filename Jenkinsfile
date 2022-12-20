pipeline { 
  agent any 
  
  stages {
    stage ('build') {
      steps {
        echo "building the project"
      } 
    }
   
    post {
      success {
        emailext body: 'this is an text email from jenkins', subject: 'test_mail', to: 'techsix87@gmail.com'
      }
    }
  }
} 
  

        
        
  
