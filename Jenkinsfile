pipeline {
    agent any


    stages {
        stage(' Helm Dependency Build') {
            steps {
                echo ' Helm Building..'
            }
        }
        stage('connecting to git') {
            steps {
                echo('connecting to git')
            }
        }
        stage('Checkout matrixnis repo') {
            steps {
                echo('checkout')
            }
        }
        stage('Helm Package') {
            steps {
                echo('Pacakging to helm')
            }
        }
        stage('Pushing Helm to ACR') {
            steps {
                echo('Pushing Help Image to Registry')


            }
        }
       
       
    }
} 
