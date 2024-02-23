pipeline {
  agent {
    label "slave-2"
  }
  stages {
    stage ("httpd") {
      steps {
        sh "sudo yum install httpd -y"
      }
    }
  }
}
