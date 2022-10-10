
pipeline {   
    agent any  
    stages{
        stage('Build'){
            steps{
                sh 'echo "Building..." '
                sh 'g++ HelloWorld.c -o HelloWorld
             }    
          }    
          stage('Test'){
              steps{
                  sh 'echo "Running..."'
                  sh './HelloWorld'
              }    
         }
    }         
}
