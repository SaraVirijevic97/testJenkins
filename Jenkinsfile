pipeline {
    agent any

    stages 
    {
        stage('Start') {
            steps {
                echo env.owner
            }
        }

        stage ('Invoke_pipeline') {
            steps {
                echo 'Hello world'
            }
        }

        stage('End') {
            steps {
                script{
                    build job: 'pipeline-2'
                }
            }
        }
    }
}
