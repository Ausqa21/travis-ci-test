pipeline {

  tools {
    maven 'Maven'
  }

  agent any
  
  stages {
    stage("build") {
      steps {
        echo 'building the app...'
        echo "app built successfully"
        sh 'mvn package'
      }
    }
    
    stage("test") {
      steps {
        echo 'testing the app...'
        echo "steadily testing..."
      }
    }
    
    stage("deploy") {
      steps {
        echo 'deploying the app...'
        echo "deployed!"
      }
    }
  }
}
