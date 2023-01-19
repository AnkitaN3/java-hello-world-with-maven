pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                    git 'https://github.com/AnkitaN3/java-hello-world-with-maven.git'

            }
        }
        stage('Create DockerImage'){
            steps{
                  sh 'docker build -t ankita2109/mytestappjava .'
            }
        }
        
    }
}
