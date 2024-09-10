pipeline {
    agent any
 
    stages {
        stage ('Master') {
            steps {
               sh 'echo "This is Master branch Pipeline"'
             }
          }
          stage('sprint1') {
             steps {
                sh 'echo "This is Sprint branch"'
             }
          }
          stage ("Development") {
              steps {
                 sh 'echo "This is development branch"'
             }
        }
    }
}
