pipeline {   
    agent any

    stages {   
        stage('DEV branch') { 
            steps { 
               sh 'echo "This is DEV branch' 
            }
        }
     
        stage('Test') { 
            steps { 
               sh 'echo "Testing application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
