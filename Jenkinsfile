pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Ensure the build.sh script is executable
                sh 'chmod +x ./build.sh'
                sh './build.sh'  // Now run the script
            }
        }
    }
}
