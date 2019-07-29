pipeline {
  agent any
  tools {
    maven 'localmaven'
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
  }
}
