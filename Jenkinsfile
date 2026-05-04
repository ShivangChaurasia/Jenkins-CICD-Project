pipeline {
agent any

stages {

    stage('Clone Repository') {
        steps {
            echo 'Cloning Repository...'
            git 'https://github.com/ShivangChaurasia/Jenkins-CICD-Project.git'
        }
    }

    stage('Build') {
        steps {
            echo 'Building Project...'
        }
    }

    stage('Test') {
        steps {
            echo 'Running Tests...'
        }
    }

    stage('Deploy') {
        steps {
            echo 'Deploying Application...'
        }
    }
}

post {
    success {
        echo 'Pipeline executed successfully!'
    }

    failure {
        echo 'Pipeline failed!'
    }
}

}
