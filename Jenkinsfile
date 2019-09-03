pipeline {
  agent any 
  stages {
    stage ('Create File') {
      steps {
      node ('master') {
        sh '''
          #!/bin/bash
          cd /u01/Git_Repo
          echo "This is just for testing purpose"
          touch test.txt
          '''
    }
      node ('SIT_App2_server') {
        sh '''
          #!/bin/bash
          cd /u01/Git_Repo
          echo "This is just for testing purpose"
          touch test.txt
          '''
    }
    }
    }
  }
}
        
        


