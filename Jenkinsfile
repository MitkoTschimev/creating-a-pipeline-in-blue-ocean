pipeline {
    agent any
    stages {
        stage('Build') {
            stages {
                stage('portal test') {
                    steps { pwd()}
                }
                stage('portal build') {
                    steps { pwd()}
                }
            }
        }
        stage('Deploy pp') {
            stages {
                stage('deploy') {
                    steps { pwd()}
                }
                stage('release') {
                    steps { pwd()}
                }
                stage('release release check') {
                    steps { pwd()}
                }
                stage('test smoke') {
                    steps { pwd()}
                }
            }
        }
        stage('Deploy p') {
            stages {
                stage('deploy') {
                    steps { pwd()}
                }
                stage('release') {
                    steps { pwd()}
                }
                stage('release release check') {
                    steps { pwd()}
                }
                stage('test smoke') {
                    steps { pwd()}
                }
            }
        }
    }
}
