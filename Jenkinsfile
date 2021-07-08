// Declarative //
pipeline {
    agent any
    triggers {
        cron('*/4 * * *')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
