pipeline {
    //runs on agent1
    agent { node { label 'agent1' } }
    stages {
        stage('build') {
            steps {
                sh 'swift build -v'
            }
        }
    }
}
