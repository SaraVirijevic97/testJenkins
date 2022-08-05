pipeline {
    agent any

    stages 
    {
        stage('Start') {
            steps {
                sh 'ls'
            }
        }

        stage ('Invoke_pipeline') {
            steps {
                echo 'Hello world'
            }
        }

        stage('End') {
            steps {
                build job: pipeline-2
            }
        }
    }
}
