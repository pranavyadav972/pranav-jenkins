pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "Hello World"'
        sh '''
                  echo "Multiline shell steps works too"
                  ls -lah
                  cd /var/www/html/pranav-jenkins
                  ls
                  git pull https://github.com/pranavyadav972/pranav-jenkins.git
                  
                '''
      }
    }

  }
}
