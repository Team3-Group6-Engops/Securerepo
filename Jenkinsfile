pipeline {
    agent any
    stages {
        stage('Main Branch Deploy Code') {
            when {
                branch 'main'
            }
            steps {
                echo "Building Artifact from Main branch"
                echo "Deploying Code from Main branch"
            }
        }
        stage('Develop Branch Deploy Code') {
            when {
                branch 'develop'
            }
            steps {
                echo "Building Artifact from Develop branch"
                echo "Deploying Code from Develop branch"
           }
        }
        stage('Feature Branch Deploy Code') {
            when {
                branch 'feature'
            }
            steps {
                echo "Building Artifact from Feature branch"
                echo "Deploying Code from feature branch"
           }
        }
    }
}
