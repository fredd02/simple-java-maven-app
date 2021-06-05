pipeline {
    agent any
    tools {
        maven 'maven3.5.4'
        jdk 'jdk1.8'
    }
    stages {
        stage('initialize'){
            steps{
                echo "PATH = ${PATH}"
                echo "M2_HOME = ${M2_HOME}"
                echo 'test2'

            }

        }
        stage ('build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }





}