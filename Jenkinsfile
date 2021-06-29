pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/sandeep4642/Java-Demo.git'
            }
        }
        stage('Build') {
            steps {
                sh ('mvn clean install')
               
            }
        }
    }
}
