// Jenkinsfile
// ----------------------------------------------------------------------
// This is as simple as it gets with declarative pipeline
// ----------------------------------------------------------------------
pipeline {
   agent {
      label 'slave2'
   }
   stages {
      stage('Say Hello') {
         steps {
            echo 'Hello World!'
         }
      }
   }
}
