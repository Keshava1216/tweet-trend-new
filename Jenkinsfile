pipeline {
    agent {
        node {
            label 'Maven'
        }
    }

    stages {
        stage('Clone-Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Keshava1216/tweet-trend-new.git'
            }
        }
    }
}
