pipeline {
    agent any

    environment {
        CS = credentials('CS') // Replace with your credentials ID
    }

    stages {
        stage('Print Environment Variable') {
            steps {
                script {
                    // Temporarily print the credential
                    echo "CS: ${CS}" // This will still be masked
                    // Unmasking (not recommended for sensitive data)
                    println "CS (unmasked): ${CS}" // This will expose the credential
                }
            }
        }
    }
}
