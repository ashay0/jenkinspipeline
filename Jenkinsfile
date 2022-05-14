pipeline {

agent any 

stages {
        stage('SCM') { 
                 steps {
                        echo "git pull by code step1"
                        echo "git pull by code step2"

               }
    }
        stage('Deploy') {
                 steps  {
                          echo "deploying my code"
         }
    }
        stage('Test') {
                steps  {
                      echo "test my final webapp"
         }
    }
stage('Deploy to Prod') {
                steps  {
                      echo "test my final webapp to webapp"
         }
   }















}