pipeline {
    agent any

    stages {

        stage('Run Scan') {

           options {
                timeout(time: 10, unit: 'MINUTES')
            }

            steps {
                git 'https://github.com/danielitogomez/automation-scanning'
                sh 'ls -alh'  
            }
            
           post {
                always {
                    sh 'echo "todo bien?"'
                }
            }
            
            
        }
        
    }
}