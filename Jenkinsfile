pipeline {
    agent any

    environment {
        CS = credentials('CS') // Replace with your credentials ID
    }

    stages {
        stage('Print Length of Secret') {
            steps {
                script {
                    // Print the length of the secret
                    def csLength = CS.length()
                    echo "Length of CS: ${csLength}"
                }
            }
        }
    }
}
