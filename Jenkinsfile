pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'welcome to my testing section'
      }
    }
    stage('build'){
      steps{
        echo 'We are building now'
      }
    }

  }
  post{
    always{
      echo 'I will always test and build here'
    }
    
  }
}
