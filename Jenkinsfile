
pipeline {
  agent { label 'Christine-Slave01-Jenkins' }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello, Jenkins!'
        sh 'touch christine.txt'
      }
    }
}
