pipeline {
    agent any
    environment{
    NEW_VERSION = '1.3.0'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo "building version $NEW_VERSION}"
            }
        }
        stage('Test1') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Test2') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
