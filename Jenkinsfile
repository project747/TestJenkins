// Declarative //
pipeline {
    agent any
    triggers {
        cron('''TZ=Europe/Kiev\n50 18 * * *''')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
