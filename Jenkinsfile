pipeline {
   agent any

   stages {
         stage('Init') {
           steps {
                sh '/usr/local/bin/docker image list'
           }
       }

       stage('Build') {
           steps {
               echo 'Building..'
           }
       }
       stage('Test') {
           steps {
               echo 'Testing..'
           }
       }
       stage('Deploy') {
           steps {
               echo 'Deploying..'
           }
       }
   }
}
