pipeline {
    agent any // This pipeline can run on any available agent

    stages{
        stage('Introduction') { // First stage: Introduction
            steps{
                echo 'Welcome this is introduction step' // Display a message
                script{
                    sleep(2) // Simulate a pause for 5 seconds
                }
            }
        }
        stage('Execution') { // Second stage: Execution
            steps{
                echo 'This is execution step' // Display a message
                script{
                    sleep(7) // Simulate a longer pause for 10 seconds
                }
            }
        }

        stage('Conclusion') { // Final stage: Conclusion
            steps{
                echo 'This is conclusion step' // Display a message
                script{
                    sleep(4) // Simulate a pause for 5 seconds
                }
                echo 'after 4 sec sleep'
            }
        }
    }
}
