pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo'
      }
    }

    stage('SAST') {
      parallel {
        stage('') {
          steps {
            sh 'echo'
          }
        }

        stage('SonarQube') {
          steps {
            sh 'echo'
          }
        }

        stage('Findbugs') {
          steps {
            sh 'echo'
          }
        }

        stage('Dependency Check') {
          steps {
            sh 'echo'
          }
        }

      }
    }

    stage('Unit Testing') {
      steps {
        sh 'echo'
      }
    }

    stage('Release') {
      steps {
        sh 'echo'
      }
    }

    stage('Deploy to Development') {
      steps {
        sh 'echo'
      }
    }

    stage('Report') {
      steps {
        sh 'echo'
      }
    }

    stage('Deploy to Testing') {
      steps {
        sh 'echo'
      }
    }

    stage('Integration Testing') {
      steps {
        echo 'Hey'
        sh 'echo'
      }
    }

    stage('UAT Testing') {
      steps {
        echo 'Hey'
      }
    }

    stage('DAST') {
      parallel {
        stage('DAST') {
          steps {
            echo 'Hey'
          }
        }

        stage('ZAP Proxy') {
          steps {
            sh 'echo'
          }
        }

      }
    }

    stage('Production Setup') {
      steps {
        sh 'echo'
      }
    }

    stage('Infrastructure Scan') {
      parallel {
        stage('Infrastructure Scan') {
          steps {
            sh 'echo'
          }
        }

        stage('OpenVAS') {
          steps {
            sh 'echo'
          }
        }

      }
    }

    stage('Compliance Scan') {
      parallel {
        stage('Compliance Scan') {
          steps {
            sh 'echo'
          }
        }

        stage('Puppet Compliance Enforcement Modules') {
          steps {
            sh 'echo'
          }
        }

      }
    }

    stage('Production Deploy Approval') {
      steps {
        sh 'echo'
      }
    }

    stage('Production Deploy') {
      steps {
        sh 'echo'
      }
    }

    stage('WAF Deploy') {
      steps {
        sh 'echo'
      }
    }

  }
}