pipeline {
    agent any // This pipeline can run on any available agent

    stages {
        stage('Introduction') { // First stage: Introduction
            steps {
                echo 'Starting the pipeline...' // Display a message
                script {
                    sleep 5 // Simulate a pause for 5 seconds
                }
            }
        }
        
        stage('Execution') { // Second stage: Execution
            steps {
                echo 'Executing the main tasks...' // Display a message
                script {
                    sleep 10 // Simulate a longer pause for 10 seconds
                }
            }
        }
        
        stage('Conclusion') { // Final stage: Conclusion
            steps {
                echo 'Pipeline execution completed.' // Display a message
                script {
                    sleep 5 // Simulate a pause for 5 seconds
                }
            }
        }
    }
}
