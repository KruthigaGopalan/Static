pipeline {
    environment {
        PATH = '/bin:/usr/coreutils/bin:.:/home/hp/meg/bin:/usr/local/bin:/usr/tandem/java/bin:/usr/local/maven/bin'}
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
