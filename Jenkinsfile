pipeline {
  agent {
    docker {
      image 'maven-6.6-jdk-8'
      args 'cujh m'
    }
    
  }
  stages {
    stage('Initialization') {
      steps {
        echo 'initialization'
        sh 'echo "welcome"'
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
    stage('error') {
      steps {
        sleep 8
      }
    }
  }
}