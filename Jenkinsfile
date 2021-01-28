pipeline {
        agent any
        environment {
            var1= '123'}
        stages {
            stage('Test Stage') {
            environment {
                var2='456'
                }
                    steps {
                        sh 'java --version'
                }
            }
        }

}
