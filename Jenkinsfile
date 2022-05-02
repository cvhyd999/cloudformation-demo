pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh '''aws cloudformation create-stack \\
  --stack-name myteststack \\
  --template-body file://ec2_parameter_example.json \\
  --region \'us-east-1\'
'''
              }
             }
            }
            }
