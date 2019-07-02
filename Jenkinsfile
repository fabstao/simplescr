pipeline {
  agent {
    node {
      label 'vps'
    }

  }
  stages {
    stage('stage1') {
      steps {
        sh '''#!/bin/bash
hostname
sleep 3
cat /proc/cpuinfo'''
      }
    }
  }
}
