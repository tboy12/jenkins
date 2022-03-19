pipeline {
    agent any
    stages {
        stage("Build"){
            steps{
                sh 'echo "Hello World"'
            }
        }
        stage("Build-2"){
            steps{
                sh '''
                    echo "Multiline shell step works too"
                    ls -lah
                    pwd
		    echo '"$LOGNAME @ localhost"'
		    
                '''
            }
        }
    }
}
