//This is my jenkins file
pipeline {
      agent any

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
         stage('Deploy-Docker') {
               steps {
                  sh 'docker run hello-world'
               }
         }
   }
}
