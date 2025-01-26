pipeline {
    agent any
  
    stages {
        
        stage("build") {
            steps {
                echo 'building the application in stage configeration...'
            }
        }
        stage("test") {
           steps {
                echo 'testing the application...'
            }
        }
        stage("deploy") {
           steps {
                echo 'deploying the application in prod...'
            }
        }
    }   
}
