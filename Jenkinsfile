pipeline {
    agent {
        image 'maven:3-alpine'
        args '-v /root/.m2:/Users/mahdir/.m2'
    }

    stages{
        stage('Build'){
            steps{
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}