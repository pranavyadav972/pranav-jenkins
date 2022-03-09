pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "Hello World"'
        sh '''
                  echo "Multiline shell steps works too"
                  ls -lah
                  cd /var/www/html
                  
                  
                  
                '''
      }
    }

  }
}
