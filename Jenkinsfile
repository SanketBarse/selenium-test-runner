pipeline{
    agent win
    stages{
        stage('running-test-cases'){
            steps{
                bat 'docker compose up'
            }
        }

        stage('tear-down'){
            steps{
                bat 'docker compose down'
            }
        }

    }
}