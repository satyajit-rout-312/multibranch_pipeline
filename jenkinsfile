pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('checkout_sourcecode') {
            steps {
                git branch: 'test1',url: 'https://github.com/satyajit-rout-312/demo1.git'
            }
        }
    }
}
