pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "mymaven"
    }

    stages {
        stage('Compile') {
            steps {
              scripts {
                    echo "COMPILING"
              }
            }
        }
        stage('Test') {
            steps {
              scripts {
                    echo "Testing"
              }
            }
        }
        stage('Package') {
            steps {
              scripts {
                    echo "Packaging"
              }
            }
        }
    }
}
