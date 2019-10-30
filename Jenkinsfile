pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error1') {
          steps {
            echo 'Prueba'
          }
        }
        stage('') {
          steps {
            sh '''#!/bin/bash
echo "HOLA"'''
          }
        }
      }
    }
  }
}