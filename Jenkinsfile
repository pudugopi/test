pipeline {
  agent any
  stages {
    stage ("Pull code from github"){
      steps{
      git credentialsId: 'gitpass', url: 'https://github.com/pudugopi/test'
      }
    }   
  }
}
