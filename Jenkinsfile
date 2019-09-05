pipeline {
    agent {
        docker{
            image 'maven:3-alpine'
            args '-v /root/.m2:/Users/Shared/Jenkins/Home/.m2'
        }
    }

    stages{
        stage('Build'){
            steps{
                sh '''
                                    echo "Multiline shell steps works too"
                                    ls -lah
                                '''
            }
        }
    }
}