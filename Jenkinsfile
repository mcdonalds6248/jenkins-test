pipeline {
    agent {
      label 'windows'
    }

    stages {
        stage('Build') {
            steps {
                // คำสั่งสำหรับการสร้างโปรเจคของคุณ
                echo 'Building..'
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
