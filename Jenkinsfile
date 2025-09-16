pipeline {
    agent any
    stages {
        stage('Run Python Script') {
            steps {
                bat 'python demo.py %X_VALUE% %Y_VALUE%'
            }
        }
    }
}
