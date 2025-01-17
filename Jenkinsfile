pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/Mohan7095954067/tweet-trend-new.git'
            }
        }
    }
}
