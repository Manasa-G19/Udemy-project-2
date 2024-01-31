pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/Manasa-G19/Udemy-project-2.git'    
            }
        }    
    }
}
