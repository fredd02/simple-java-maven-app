pipeline {
    agent any
    tools {
        maven 'maven3.5.4'
        jdk 'jdk1.8'
    }
    triggers {
            pollSCM('') //Empty quotes tells it to build on a push
        }
    stages {
        stage('initialize'){
            steps{
                echo "PATH = ${PATH}"
                echo "M2_HOME = ${M2_HOME}"
                echo 'test5'

            }

        }
        stage ('build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }





}