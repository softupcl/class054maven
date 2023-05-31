pipeline {
    agent any 
 
    environment {
        MAVEN_HOME="/opt/homebrew/Cellar/maven/3.9.2/libexec"
    }
    stages {
        stage('Inicio') {
            steps{
                echo 'Iniciando ciclo'
            }
            
        }
        stage('Build') { 
            steps {
                sh '${MAVEN_HOME}/bin/mvn -B -DskipTests clean package'
                //sh 'mvn -B -DskipTests clean package' 
            }
        }

    }
}
