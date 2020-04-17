pipeline {
  agent any
  stages {
    stage ("Pull code from github"){
     git credentialsId: 'gitpass', url: 'https://github.com/pudugopi/test'
    }
  }
}
