pipeline {
  agent {
    label 'main'
  }

  environment {
    APP_ORIGIN_WORKSPACE = "${env.WORKSPACE}"
  }

  stages {
    stage('Initial Stage') {
      steps {
        echo "Starting initial stage"
        echo "APP_ORIGIN_WORKSPACE = ${APP_ORIGIN_WORKSPACE}"
      }
    }
  }
}
