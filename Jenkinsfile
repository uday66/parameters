pipeline {
    agent any
    parameters {
       choice(choices: 'Integration', description: 'Choose the environment', name: 'ENVIRONMENT')
       booleanParam(name: 'DEBUG', defaultValue: false, description: 'check the box if you want to debug')
       booleanParam(name: 'DEPLOY', defaultValue: false, description: 'check the box if you want to deploy')
       string(name: 'Branch   ', defaultValue: 'Default ', description: 'Select required branch.')


  }
    
  stages {
        stage('Example') {
            steps {
                echo "Hello ${params.ENVIRONMENT}"
            }
            }
            }
        }
