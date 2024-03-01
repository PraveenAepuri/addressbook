pipeline {
    agent none

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "mymaven"
    }

    stages {
        stage('Compile') {
            steps {              
              script{
                     echo "COMPILING"
              }             
            }
        }
        stage('Test') {
            steps {           
              script{
                   echo "RUNNING THE TC"
                }              
            }            
        }
        stage('Package') {
            steps {              
                script{
                   echo "Creating the package"
                  }             
                }
            }            
        }
}
