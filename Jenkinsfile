pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
          withMaven(maven: 'Maven3') {
    echo 'mvn clean install'
              sh 'mvn clean verify'
}
      }
    }

  }
}
