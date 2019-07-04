pipeline {
  agent {
    none
  }
  stages {
    stage('VM+BM_build') {
      steps {
        node('ubuntuvm') {
          sh '''#!/bin/bash
hostname
sleep 3
uname -a'''
        }
        node('wolfpass.512'){
          sh '''#!/bin/bash
hostname
sleep 3
uname -a'''
             }
      }
    }
  }
}
