<<<<<<< HEAD

=======
>>>>>>> 34ed6bbc0f28b9e7b7e8767520ddaa6541112647
pipeline {
  agent any

  triggers {
    pollSCM('* * * * *')
  }

  stages {
    stage('Checkout') {
      steps {
        git branch: 'main', 
        url: '<URL>'
      }
    }
    stage('Build') {
      steps {
        sh '<COMMAND>'
      }
    }
    stage('Test') {
      steps {
        sh '<COMMAND>'
      }
    }
    stage('Deploy') {
      steps {
        deploy adapters: [tomcat9(credentialsId: '<NAME>', url: '<URL>')], contextPath: null, war: 'path/to/war'
      }
    }
  }
<<<<<<< HEAD
}
=======
}
>>>>>>> 34ed6bbc0f28b9e7b7e8767520ddaa6541112647
