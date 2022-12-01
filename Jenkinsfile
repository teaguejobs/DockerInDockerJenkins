pipeline {
   agent {
      'dockerfile true'
   }

   stages {
      stage('Hello') {
         steps {
                sh 'java -version'
                echo "Get working directory"
                sh 'pwd'
         }
      }
   }
}
