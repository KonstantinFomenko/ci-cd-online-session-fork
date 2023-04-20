pipeline {
  agent any
  stages {
    stage('') {
      steps {
        script {
          checkout scm

          def customImage = docker.build("${registry}:${env.BUILD_ID}")
        }

      }
    }

  }
  environment {
    registry = 'konstantinfomenko / ci-cd-online-session'
  }
}