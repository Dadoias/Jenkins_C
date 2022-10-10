
pipeline {    
          agent any  

          stages{
             stage('Build'){
                steps{
                 echo "Building..."
                 sh 'chmod +x Linux-Build.sh'
                 sh 'Linux-Build.sh'
          }    }    stage('Test'){
            steps{
                sh 'echo "Running..."'
                sh 'chmod +x Linux-Run.sh'
                sh 'Linux-Run.sh'
           }    
  }
}
