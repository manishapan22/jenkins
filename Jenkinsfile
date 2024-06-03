pipeline{
    agent any
    stages {
        stage('submit stack') {
            steps {
                bat "aws cloudformation create-stack --stack-name MyStack --template-body file://ec2cft.yaml --region 'eu-north-1'"
            }
        }

    }
}
