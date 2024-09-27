pipeline {
       agent any
       stages {
           stage('Build') {
               steps {
                   git 'https://github.com/SplinteeX/DockerSetUp.git'
                   sh 'mvn clean install'
               }
           }
       }
   }