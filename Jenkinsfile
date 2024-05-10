pipeline{
    agent any
    stages{
        stage('cleanup'){
            steps{
                cleanWs()
            }
        }
        stage('check-file'){
            steps{
                sh 'touch testing.txt'
                sh 'ls -lrt'
                sh 'ls -lrt'
            }
        }
    }
}
