pipeline {
agent any
  stages {
    stage('Source') { 
      steps {
        echo 'Reading from Git'    
        fileExists 'https://github.com/lokesh125656/AutomationV7.git/Jenkinsfile'

      }
    }
    stage('Compile') {
     
      steps {
        // run Gradle to execute compile and unit testing
        echo 'Reading from Git compiled'    
      }
    }
  }
}
