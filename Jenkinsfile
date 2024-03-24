pipeline {
  agent any
  tools { 
      maven 'SDK Man Maven' 
      jdk 'SDK Man JDK' 
  }
  stages {
    stage('check out') {
      steps {
        git(url: 'https://github.com/AdrianGri/maven-samples-A6', branch: 'master')
      }
    }
  }
}
