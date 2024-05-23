pipeline{
    agent{
        label 'win'
    }
    stages{
        stage('running-test-cases'){
            steps{
                bat 'docker compose up -d'
            }
        }
        

    }

    post{
        success {
        bat "docker compose down"
        }
    }
}