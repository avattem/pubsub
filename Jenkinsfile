pipeline {
  agent {
    docker {
      image 'maven-6.6-jdk-8'
    }
    
  }
  stages {
    stage('Initialization') {
      steps {
        echo 'initialization'
      }
    }
    stage('testing') {
      steps {
        echo 'hellooo'
      }
    }
    stage('report') {
      steps {
        echo 'reports generation'
        echo 'hiiii '
      }
    }
    stage('') {
      steps {
        sleep 8
      }
    }
  }
}