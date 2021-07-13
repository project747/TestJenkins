// Declarative //
pipeline {
    agent any
    triggers {
        cron('''TZ=Europe/Kiev\n50 20 * * *''')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
