pipeline {
    agent any 
    stage('Inicio') {
            steps{
                echo 'Iniciando ciclo'
            }
            
        }
        stage('Build') { 
            steps {
                withMaven {
                    sh 'mvn clean package' 
                }    
                
            }
        }

    }
}
