pipeline {
    agent any  // Execute the pipeline on any available agent

    stages {
        stage('Build Information') {
            steps {
                echo "Build Number: ${BUILD_NUMBER}"  // Print build number
                sh 'ls -l'                          // List directory contents with long format
            }
        }
    }
}
