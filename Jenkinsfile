pipeline {
    agent any

    stages {
        stage('Build pdf') {
            steps {
                sh 'pdflatex -shell-escape main.tex'
            }
        }
    }
}