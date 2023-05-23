pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: '20dfbed1-1d64-465f-8a38-7413dc8367e4', url: 'https://github.com/Karmacode00/RepoTestJenkins.git'
            }
        }
    }
}