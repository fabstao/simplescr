pipeline {
  agent {
    node {
      label 'wolfpass.512'
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