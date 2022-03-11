pipeline {
    agent any
    stages {
        stage('Newman TEST') {
            steps {
                nodejs('NodeJS') {
                	sh "newman run mi-indicador.json"
                }
            }
        }
    }
}
