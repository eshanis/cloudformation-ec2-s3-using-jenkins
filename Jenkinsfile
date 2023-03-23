pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name eshani-ec2-s3-example1 --template-body file://01_ec2.yaml --region 'us-east-1'"
              }
         }


     }
}
