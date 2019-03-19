pipeline{
    agent none
    stages{
        stage('test'){
            steps {
                powershell 'mvn --version'
                powershell 'node --version'
            }
        }
    }
}