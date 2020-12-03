pipeline {
    agent any 
    tools {
        maven 'M3'
        jdk
    }
    stages {
        stage("build") {
            steps {
                echo 'building the application'
                sh mvn install
            }
        }

        stage("test") {
            steps {
                echo 'testing the application...'
            }
        }
        
        stage("deploy") {
            steps{
                echo 'deploying the application...'
            }
        }
    }
}