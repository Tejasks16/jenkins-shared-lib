@Library('library-demo') _


pipeline {
    agent any
    stages {
        // stage('Demo') {
        //     steps {
        //         echo 'Executing a shared lib function'
        //         sayHello 'Devops'

        //     }
        // }
        stage('Checkout') {
            steps {
                sh 'rm -rf hello-world-war'
                sh 'git clone https://github.com/Tejasks16/hello-world-war.git'
                sh 'https://github.com/Tejasks16/hello-world-war.git'
            }
        }

        stage('Build') {
            steps {
                script {
                    build()
                }
            }
        }
    }
}
