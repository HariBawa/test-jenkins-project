pipeline {
   agent {label 'hsbawa-mac-w-docker'}

   stages {
         stage('Init') {
           steps {
                sh 'echo $USER'
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
