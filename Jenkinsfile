pipeline {
  agent any
  stages {
    stage('checkout SCM') {
      steps {
        git(url: 'https://github.com/jagan474633/spring-petclinic.git', branch: 'develop')
      }
    }
  }
}