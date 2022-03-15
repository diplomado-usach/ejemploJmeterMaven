pipeline {
    agent any
    stages {
        stage('Jmeter') {
            steps {
                    script {
                        sh './mvnw verify -Pperformance'
                    }
            }
        }

    }
}