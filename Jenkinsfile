pipeline {
        agent any
        options { skipDefaultCheckout()
                  buildDiscarder(logRotator(numToKeepStr:'25'))
        }
        stages {
            // Add jenkins environment variables to configuration
            stage('Env') {
                steps {
                    script {
                        checkout scm
                        echo "Hello"

                    }
                }
            }
        }
}
