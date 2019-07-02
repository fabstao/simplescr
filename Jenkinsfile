pipeline {
  agent {
    node {
      label 'vmslave2'
    }

  }
  stages {
    stage('stage1') {
      steps {
        sh '''#!/bin/bash
hostname
sleep 3
cat /proc/cpu'''
      }
    }
  }
}