pipeline {
    agent any
    stages {
        stage("Build Master") {
            when {
              tag "3.0"
            }
            steps {
                echo "Hello World Building Tag"
            }
        }
    }
  }

