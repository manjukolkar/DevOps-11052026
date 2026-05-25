pipeline{
    agent any

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
                sh 'du -sh'
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
