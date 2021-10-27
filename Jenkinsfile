pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo 'hi to all'
            }
      
         }
    
      
        stage('Test') {
            steps {
                echo 'Test World'
                echo 'hi to all'
            }
           
         }
          stage('Test1') {
            steps {
                echo 'testingd'
                echo 'hi to all'
            }
         }
         stage('Test2') {
            steps {
                echo 'testingd'
                echo 'hi to all'
            }
         }
      
    }
     post {
  success {
    // One or more steps need to be included within each condition's block.
      mail bcc: '', body: 'Test mail for pipeline', cc: '', from: '', replyTo: '', subject: 'Test mail', to: 'vikram.klsn@gmail.com'
  }
}
}
