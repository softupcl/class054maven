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
                $PATH
                sh 'mvn -B -DskipTests clean package' 
            }
        }

    }
}
