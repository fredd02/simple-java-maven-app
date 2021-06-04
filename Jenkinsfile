pipeline {
    agent any
    tools {
        maven 'maven3.5.4'
        jdk 'jdk1.8'
    }
    stages {
        stage('initialize'){
            steps{
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                 '''
            }

        }
        stage ('build') {
            steps {
                echo 'this is a minimal pipeline'
            }
        }
    }





}