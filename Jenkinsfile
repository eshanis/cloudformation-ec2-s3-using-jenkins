pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name eshani-ec2-s3-example2 --template-body file://ec202-s3bucket.yaml --region 'us-east-1'"
              }
         }


     }
}
