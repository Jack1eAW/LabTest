pipeline {
    //runs on agent1
    agent { node { label 'agent1' } }
    stages {
        stage('build') {
            steps {
                sh xcodebuild -scheme Test -configuration Debug build test \
                              -destination 'platform=iOS Simulator,name=iPhone 14' 
            }
        }
    }
}
