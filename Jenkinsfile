pipeline {
  agent any 
  tools {
    maven 'maven'
  }
  stages {
    stage ('compile') {
      steps {
        sh 'mvn compile' 
      }
    }
    stage ('testing') {
      steps {
        sh 'mvn test'
      }
    } 
    stage ('package') {
      steps {
        sh 'mvn package'
      }
    }
    stage ('install') {
      steps {
        sh 'mvn install'
      }
    }
  }
}
      
