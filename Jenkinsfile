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
                #!/bin/sh
                sh 'mvn -B -DskipTests clean package' 
            }
        }

    }
}
