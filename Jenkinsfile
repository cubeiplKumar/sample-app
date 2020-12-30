pipeline {
    agent any
    tools{
        //maven path in jenkins 
        maven 'maven3'
    }
    stages{
        stage('Build'){
            steps{
               sh script: 'mvn clean package'     
            }
            
        }
    }
}
