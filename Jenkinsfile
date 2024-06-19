pipeline{
  agent any
  stages{
    stage("Build"){
      steps{
        nodejs("NodeJS"){
          echo "Building application...."
          sh "npm install"
        }
      }
    }
  }
} 
