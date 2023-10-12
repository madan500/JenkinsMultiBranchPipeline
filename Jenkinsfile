pipeline {   
    agent any

    stages {   
        stage('DEV branch') { 
            steps { 
               bat 'echo "This is DEV branch' 
            }
        }
     
        stage('Test') { 
            steps { 
               bat 'echo "Testing application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                bat 'echo "Deploying application..."'
            }
        }  
    }
}
