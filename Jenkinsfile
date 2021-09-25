pipeline{
    agent any
    stages{
        stage('deloy job'){
            steps{
                echo "deploy job in test env"
            }
        }
        stage('call selenium job'){
            steps{
                build 'selenium-job'
            }
        }
    }
}
