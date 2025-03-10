pipeline {
    agent any

    stages {
        stage('Build pdf') {
            steps {
                sh 'pdflatex -shell-escape main.tex'
            }
        }
        stage('Save artifact') {
            steps {
                archiveArtifacts 'main.txt'
            }
        }
    }
}