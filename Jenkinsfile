pipeline {
  agent any

  tools {
        maven 'Maven'
    }
  
  stages {
    stage("build"){
      steps{
        sh 'mvn -v'
      }
    }

    stage("test"){
      steps{
        echo 'Testing the application'
      }
    }

    stage("deploy"){
      steps{
        echo 'Deploying the application'
      }
    }
    
  }

}
