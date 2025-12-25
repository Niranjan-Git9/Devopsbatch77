pipeline {
    agent any

    stages {
        stage('edited dev branch') {
           steps {
              sh 'echo "bye branch"'
           }

        }

        stage('dev') {
            steps {
               sh 'echo "dev application ... "'

            }

         }

         stage("Deploy application") {
              steps {
                 sh 'echo "Deploying application ... "'

             }

          }

      }

}
