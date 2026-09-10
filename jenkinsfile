pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building Product Catalogue'
                echo 'Building Product Description'
                echo 'Building Product Search'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Product Catalogue'
                echo 'Testing Product Description'
                echo 'Testing Product Search'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Product Catalogue'
            }
        }
    }
}