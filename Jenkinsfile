pipeline {
    agent {
        docker {
            image 'openjdk:16-jdk-slim' // Gunakan gambar Java, misalnya OpenJDK 16
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'javac HelloWorld.java' // Ganti perintah untuk membangun proyek Java, misalnya dengan menggunakan 'javac'
            }
        }
    }
}