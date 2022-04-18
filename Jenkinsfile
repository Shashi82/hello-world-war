pipeline {
  agent { label 'java' }
  stages {
        stage('checkout') {
        steps {
             sh 'git clone https://github.com/Shashi82/hello-world-war.git'
        }
      }
  stage('build') {
     steps {
                sh 'mvn clean package'
            }
        }
  stage ('deploy') {
    steps {
                sh 'cp source_path destination_path'
            }
        }
     }
 }
