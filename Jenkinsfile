pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'su apt install -y npm' 
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
