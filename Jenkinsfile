pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh git clone https://github.com/CodeWithBanchi/Vehireg_API  C:\Users\Banchi\Desktop\editys\ltrm
            }
        }
    }
}
