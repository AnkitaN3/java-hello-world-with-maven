pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                    git 'https://github.com/AnkitaN3/java-hello-world-with-maven.git'

            }
        }
        stage('mvn package'){
            steps{
                  sh 'mvn package'
            }
        }
    }
}
