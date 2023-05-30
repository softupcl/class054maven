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
                zsh 'mvn -B -DskipTests clean package' 
            }
        }

    }
}
