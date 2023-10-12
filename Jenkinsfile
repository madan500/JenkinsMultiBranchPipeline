pipeline {   
    agent any

    stages {   
        stage('Master branch') { 
            steps { 
               bat 'echo "This is master branch' 
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