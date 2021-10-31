# Runing Jenkins in a Docker Container 
pipeline {
    agent any 
    stages {
        stage ("Build"){
            steps {
                 echo  ' Building initialised '
            }
        }
        stage("Test"){
            steps {
                echo  ' Testing Script using Karma and Mocho '
            }

        }
        stage("Deploying"){
            steps {
                echo  ' Deploying to AWS EKS '
            }
        }
    }
}
