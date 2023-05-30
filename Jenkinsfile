pipeline {
    agent any 
    stages {
        stage('Inicio') {
            steps{
                echo 'Iniciando ciclo'
               
            }
            
        }
        stage('Build') { 
            steps {
                environment {
                    MAVEN_HOME="/opt/homebrew/Cellar/maven/3.9.2/libexec"
                    M2_HOME="/opt/homebrew/Cellar/maven/3.9.2/libexec"
                    PATH=$PATH:$M2_HOME/bin
                }
                sh 'mvn -B -DskipTests clean package' 
            }
        }

    }
}
