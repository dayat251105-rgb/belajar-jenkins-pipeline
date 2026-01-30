pipeline {
    agent {
      node {
        lable "linux && java11"
      }
    }
    stages {
        stage("Hello") {
            steps {
                echo("Hello Pipeline")
            }
        }
    }
}