pipeline {
    agent any
    stages {
        stage('Newman TEST') {
            steps {
                nodejs('NodeJS') {
                	newman run mi-indicador.json
                }
            }
        }
    }
}
