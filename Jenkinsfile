pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Worldss'
                git branch: 'main', credentialsId: '47f9858f-9dfd-4b0f-a4d3-ddd52bd4ce65', url: 'https://github.com/DiegoStudy/Fork.git'
            }
        }
    }
}