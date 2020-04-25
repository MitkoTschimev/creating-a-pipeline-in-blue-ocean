pipeline {
    agent any
    stages {
        stage('Build') {
            stages {
                stage('portal test') {
                    steps { pwd()}
                }
            }
            stages {
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
            }
            stages {
                stage('release') {
                    steps { pwd()}
                }
            }
            stages {
                stage('release release check') {
                    steps { pwd()}
                }
            }
            stages {
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
            }
            stages {
                stage('release') {
                    steps { pwd()}
                }
            }
            stages {
                stage('release release check') {
                    steps { pwd()}
                }
            }
            stages {
                stage('test smoke') {
                    steps { pwd()}
                }
            }
        }
    }
}
