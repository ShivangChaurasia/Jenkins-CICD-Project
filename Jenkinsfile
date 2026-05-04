pipeline {
agent any

```
stages {

    stage('Clone Repository') {
        steps {
            git 'https://github.com/ShivangChaurasia/Jenkins-CICD.git'
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
```

}
