pipeline {
  agent any 
  node ('829zmsh-t-app1.cloudnl.digital.kpn.org') {
    stages {
      
      stage ('Create File') {
        sh '''
          #!/bin/bash
          cd /u01/Git_Repo
          echo "This is just for testing purpose"
          touch test.txt
          '''
    }
      stage ('Create Dir') {
        sh '''
        #!/bin/bash
        cd /u01/Git_Repo
        mkdir Deploy
        chmod 744 Deploy
        '''
      }
    }
  }
}
        
        


