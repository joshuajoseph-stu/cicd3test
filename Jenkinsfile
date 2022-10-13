pipeline {
  agent any
  tools {
    maven 'maven' 
  }
  stages {
    stage ('Build') {
      steps {
        bin 'mvn clean install'
      }
    }
  }
}
