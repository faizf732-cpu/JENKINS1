pipeline {
    agent any
    stages {
        stage('Environment Check') {
            steps {
                echo 'Checking Python version...'
                sh 'python --version' 
            }
        }
        stage('Install Dependencies') {
            steps {
                echo 'This is where you would run: pip install pandas scikit-learn'
            }
        }
    }
}
