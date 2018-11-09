pipeline {
   agent any

   stages {
         stage('Init') {
           steps {
                sh 'docker image list'
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
