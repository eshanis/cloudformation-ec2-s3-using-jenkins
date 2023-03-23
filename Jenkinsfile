pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name eshani-ec2-s3-example202 --template-body file://ec2-s3bucket.yaml --region 'us-east-1'"
              }
         }


     }
}
