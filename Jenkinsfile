pipeline{
    agent {
        label 'slave'
    }

    stages{
        stage('hostname'){
            steps{
                sh 'hostname'
            }
        }
        stage('Memory usage'){
            steps{
                sh 'free -h'
            }
        }
        stage('disk usage'){
            steps{
                sh 'df -kh'
            }
        }
        stage('cpu details'){
            steps{
                sh 'lscpu'
            }
        }
        stage('Host Ip'){
            steps{
                sh 'hostname -I'
            }
        }
    }
}
