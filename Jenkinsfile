pipeline {
  agent any 
  stages {
    stage ('Create File') {
      node ('829zmsh-t-app1.cloudnl.digital.kpn.org') {
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
        
        


