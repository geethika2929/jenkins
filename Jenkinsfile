pipeline {
    agent any
    triggers {
        pollSCM('H/5 * * * *')
    }
    stages {
        stage('Build') {
            steps {
                echo "Author: Abhiram Ayla"
                echo "Roll Number: SE22UARI005"
                echo "Building.."
                sh '''
                echo "Building from Jenkins file"
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo "Testing the build triggered from Jenkins file."
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}


