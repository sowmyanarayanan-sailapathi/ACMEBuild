pipeline {
    agent any


    stages {
        stage('Check Out') {
            steps {
                git 'https://github.com/sowmyanarayanan-sailapathi/ACMEBuild'
            }
        }
            stage ('Build'){
                steps{
                    bat 'mvn clean install'
                }
            }
        }
    }
