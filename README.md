# one2onetool
pipeline {
    agent any 

stages{
        stage ('Install Dependcies'){
         steps {
            sh 'npm install' 
}
        }
    
        stage('Test') { 
            steps {
                sh 'echo "testing application.."'
            }
        }
        stage('Delpoy nodejs application') { 
            steps {
                sh 'echo "deploying application.."'
    }
}
}
}
