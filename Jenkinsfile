pipeline {
  agent {
    none
  }
  stages {
    stage('VM_stage') {
      agent {
        node {
        label 'ubuntuvm'
      }
    }
      steps {
        sh '''#!/bin/bash
hostname
sleep 3
uname -a'''
      }
    }
    stage('Bare_metal_stage') {
      agent {
        node {
        label 'wolfpass.512'
      }
    }
      steps {
        sh '''#!/bin/bash
hostname
sleep 3
uname -a'''
      }
    }
    
  }
}
