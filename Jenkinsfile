pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                echo "========executing A========"
            }
            
        }
        stage("B"){
            steps{
                echo "========executing A========"
            }
            
        }
        stage("C"){
            steps{
                echo "========executing A========"
            }
            
        }
        stage("D"){
            steps{
                echo "========executing A========"
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