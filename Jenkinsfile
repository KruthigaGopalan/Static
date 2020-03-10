pipeline {
    environment {
        PATH =""C:\Program Files (x86)\Jenkins\workspace\Static_master";${env.PATH}"}
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
