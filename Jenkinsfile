pipeline {   
    agent any

    stages {   
        stage('Dev branch') { 
            steps { 
               sh 'echo "This is Dev branch test..........."' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
