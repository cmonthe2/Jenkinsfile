pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation deploy --template-file module.yml template.json --stack-name my-new-stack"
              }
             }
            }
            }
