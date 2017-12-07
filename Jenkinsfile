pipeline {
    agent any
    parameters {
       choice(choices: 'Integration', description: 'Choose the environment', name: 'ENVIRONMENT')
       booleanParam(name: 'DEBUG', defaultValue: false, description: 'debug here')
       booleanParam(name: 'DEPLOY', defaultValue: false, description: 'deploy here')
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
