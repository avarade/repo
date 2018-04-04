pipeline {
  agent any
  stages {
    stage('S1') {
      parallel {
        stage('S1') {
          steps {
            sleep 1
          }
        }
        stage('s2') {
          steps {
            sleep 1
          }
        }
        stage('s3') {
          steps {
            sleep 1
          }
        }
      }
    }
    stage('s4') {
      parallel {
        stage('s4') {
          steps {
            sleep 1
          }
        }
        stage('s5') {
          steps {
            sleep 1
          }
        }
      }
    }
    stage('s6') {
      parallel {
        stage('s6') {
          steps {
            sleep 1
          }
        }
        stage('s7') {
          steps {
            sleep 1
          }
        }
        stage('s8') {
          steps {
            sleep 1
          }
        }
        stage('s9') {
          steps {
            sleep 1
          }
        }
        stage('s10') {
          steps {
            sleep 1
          }
        }
      }
    }
  }
}