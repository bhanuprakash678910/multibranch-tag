pipeline {
    agent any
    stages {
        stage("Build Master") {
            when {
              tag "Rel-1.0"
            }
            steps {
                echo "Hello World Building Tag"
            }
        }
    }
  }

