pipeline {
    agent any
    stages {
        stage('Clone'){
            steps {
                git 'https://github.com/nguyen-hien-190590/hello_jenkins_docker.git'
            }
        }
    }
    post {
        always {

            mail bcc: '', body: 'Jenkins build', cc: '', from: '', replyTo: '', subject: 'Jenkins_build', to: 'hiennguyenthanh190590@gmail.com'
        }
    }
}
