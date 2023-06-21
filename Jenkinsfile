pipeline{
    agent any
    stages{
        stage('hello'){
            steps{
                echo "Hello lets work with jenkins"
            }
        }

        stage('checkout repo') {
            steps{
                git branch: 'main' ,url: 'https://github.com/DRuchi-1/jenkins-devops.git'
            }
        }
    }
}
