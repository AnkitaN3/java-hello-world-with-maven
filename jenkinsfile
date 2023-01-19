pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                    git 'https://github.com/AnkitaN3/java-hello-world-with-maven.git'

            }
        }
        stage('Maven Test'){
            steps{
                  sh 'mvn test'

            }
        }
        stage('Maven Build'){
            steps{
                    sh 'mvn package'

            }
        }
        stage('Maven Deploy'){
            steps{
                    echo "Deploying war file to the server"

            }
        }
    }
}
