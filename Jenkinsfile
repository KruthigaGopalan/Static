pipeline {
    environment {
    PATH ="C:\\Program Files\\Git\\usr\\bin;C:\\Program Files\\Git\\bin;${env.PATH}",
    agent any
    stages {
        stage ('Build') {
            steps {
                sh 'echo "Hello world"'
                sh '''
                    echo "Multi-line shells steps work too"
                    ls -lah
                    '''
            }
       }
    }
}  
