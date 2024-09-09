
pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                git "https://github.com/punitha201120/trial.git"
            }
        }
        stage('type msg') {  // Missing closing quote fixed
            steps {
                echo "hello this is from pipeline"
            }
        }
    }
}
