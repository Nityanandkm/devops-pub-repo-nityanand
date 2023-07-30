pipeline{
    agent any
    stages{
        stage("Building war file"){
            steps{
                echo "war file builded successfully"
            }

        }

    stage("Testing war file"){
            steps{
                echo "war file tested successfully"
            }

        }
    stage("Deploying war file to tomcat"){
            steps{
                echo "Deployed successfully"
            }

        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}