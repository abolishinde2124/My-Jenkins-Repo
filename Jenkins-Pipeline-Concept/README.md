## 1) Declarative Pipeline:<br>

Uses a simpler and more structured syntax.<br>
Enforces a specific structure, making it easier to write and maintain.<br>
Syntax example:<br>

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}

## 2) Scripted Pipeline:<br>

More flexible but with complex Groovy-based syntax.<br>
Typically used by advanced users needing detailed control over the pipeline.<br>
Syntax example:<br>

node {
    stage('Build') {
        echo 'Building...'
    }
    stage('Test') {
        echo 'Testing...'
    }
    stage('Deploy') {
        echo 'Deploying...'
    }
}

