pipeline {
    agent any

    environment {
        CS = credentials('CS') // Replace with your credentials ID
    }

    stages {
        stage('Display CS') {
            steps {
                echo "CS: ${CS}"
            }
        }
    }
}
