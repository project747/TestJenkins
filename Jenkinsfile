// Declarative //
pipeline {
    agent any
    triggers {
        cron('''TZ=Europe/Kiev\n50 25 * * *''')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
