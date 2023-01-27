pipeline {

  agent {
  label 'ansible'
  }

  stages {

    stage('Hello1') {
      steps {
        echo 'Hello World'
      }
    }

     stage('Hello2') {
          steps {
            echo 'Hello World'
          }
        }
         stage('Hello3') {
              steps {
                echo 'Hello World'
              }
            }

}
post {
always {
echo "send an email"
}
}
}