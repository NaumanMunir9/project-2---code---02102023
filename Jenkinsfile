pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/NaumanMunir9/project-2---code---02102023'
            }
        }
    }
}
