pipeline {
    agent {
        label 'master'
    }

    stages {
        stage('Deploy to nginx') {
            steps {
                sh 'scp html_files/index.html root@10.0.0.53:/var/www/html/index.html'
            }
        }
    }
}

