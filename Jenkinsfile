pipeline {
    agent any 
    tools { 
      maven : 'MAVEN_HOME' 
      jdk : 'JAVA_HOME' 
    }
    stages {
        stage('Inicio') {
            steps{
                echo 'Iniciando ciclo'
            }
            
        }
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }

    }
}
