pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation deploy --template-file s3-bucket.yml --stack-name patrick"
              }
             }
            }
            }
