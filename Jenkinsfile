pipeline {
  agent any 
    stages {
      stage ('First Stage') {
        steps {
          echo 'Hello From Jenkins Pipeline'
        }
        stage ('Second Stage') {
          steps {
            echo 'Just testing whether the SCM polling works or not'
          }
        }
      }
    }
}
