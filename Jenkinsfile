pipeline {
  agent {
    node {
      label 'wolfpass.512'
    }
  }
  
  stages {
    stage('Bare_metal_stage') {
      steps {
        sh '''#!/bin/bash
hostname
sleep 3
uname -a'''
      }
    }
    stage('VM_stage') {
      steps {
        sh '''#!/bin/bash
hostname
sleep 3
uname -a'''
      }
    }
  }
}
