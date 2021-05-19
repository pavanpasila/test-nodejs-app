pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps {
	   sh 'echo "Welcome to Hello World"'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
	   sh 'echo "installation done"'
         }

     }
  
   	}

   }
