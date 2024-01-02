pipeline {
    agent {
      label 'windows'
    }

    stages {
        stage('Build') {
            steps {
                // คำสั่งสำหรับการสร้างโปรเจคของคุณ
                echo 'Building..'
                git 'https://github.com/nonafk/CQRS_Mediator_Dapper_Api.git'
                bat "dotnet restore CQRS_Mediator_Dapper_Api.sln"
                bat "dotnet build"
                bat "dotnet publish"
            }
        }
        stage('Test') {
            steps {
                // คำสั่งสำหรับการทดสอบโปรเจคของคุณ
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                // คำสั่งสำหรับการปรับใช้งานโปรเจคของคุณ
                echo 'Deploying....'
            }
        }
    }
}
