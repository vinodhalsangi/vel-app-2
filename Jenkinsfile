pipeline {
  agent {
    label "slave-1"
  }
  stages {
    stage ("httpd") {
      steps {
        sh "sudo yum install httpd -y"
      }
    }
  }
}
