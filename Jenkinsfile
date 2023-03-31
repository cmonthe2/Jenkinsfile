pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation deploy --template-file template.yaml --stack-name static-website"
              }
             }
            }
            }
