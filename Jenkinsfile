pipeline {
    agent {
        docker{
            image 'node:10'
            args '-p 20000:8080'
        }
    }

    stage('build') {
      steps {
        sh 'npm run build'
      }
    }
}