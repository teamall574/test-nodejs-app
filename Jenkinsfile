pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'sudo apt install -y npm ' 
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
         }

     }
  
   	}

   }
