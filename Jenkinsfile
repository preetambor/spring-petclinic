#!groovy
pipeline {
    agent any
   stages {     
    stage('Maven Install') {
      agent {         
       docker {          
         image 'maven:3.9.9'         
     }       
  }       
  steps {
       sh 'mvn clean install'
       }
     }
   }
 }
