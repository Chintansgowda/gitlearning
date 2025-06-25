pipeline{
    agentany

    stages{
        stage('p-hname'){
            steps{
                sh 'hostname'
            }
        }
        stage('ip-address'){
            steps{
                sh 'hostname -I'
            }
        }
        stage('cpu-details'){
            steps{
                sh 'lscpu'
            }
        }
        stage('disk-usage'){
            steps{
                sh 'df -h'
            }
        }
        stage('mem-usage'){
            steps{
                sh 'free -h'
            }
        }
    }
}
