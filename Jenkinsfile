Pipeline {
  agent any 
  
  stages {
    stage ('build') {
      steps {
        echo "building the project"
      }
    }
    post {
      success {
        emailext body: 'Test email from jenkins', subject: 'Test_email', to: 'techsix87@gmail.com' 
      }
    }
  }
} 
        
        
  
