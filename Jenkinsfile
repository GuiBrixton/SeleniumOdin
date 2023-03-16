pipeline {
    agent any
  stages {
    stage('Cloning Git') {
      steps {
        echo '***************************************************************'
        echo '******            CLONANDO REPOR DOCKER COMPOSE          ******'
        echo '***************************************************************'
        sh 'mkdir /tmp/test'
        //sh "git clone https://github.com/GuiBrixton/SeleniumOdin.git configuracion --branch main"
      }
    }

    stage('Delete Repo') {
      steps {
        echo '***************************************************************'
        echo '******            CLONANDO REPOR DOCKER COMPOSE          ******'
        echo '***************************************************************'
      }
    }

    stage('Build') {
      steps {
        echo '***************************************************************'
        echo '******            CLONANDO REPOR DOCKER COMPOSE  FIM     le******'
        echo '***************************************************************'
        }

      }
    }
    post {
    always {
        echo '***************************************************************'
        echo '******         CLONANDO REPOR DOCKER COMPOSE  DESTROY ******'
        echo '***************************************************************'
       // sh 'docker-compose -f integration/docker-compose.yml down -v'
    }
}
  }
