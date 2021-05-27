pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "myjobmaven"
            }
          
          steps {
             
                echo "my fix branch"
          }
        }
   }
}
