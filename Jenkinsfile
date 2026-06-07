pipeline {

    agent any

    stages {

        stage('Build') {

            steps {

                sh '/usr/local/bin/mvn  clean package'

            }

        }

        stage('Docker Build') {

            steps {

                sh 'docker build -t spring-demo .'

            }

        }

    }

}
