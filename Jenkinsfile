pipeline {
    agent {
        label 'agent_1'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('list files') {
            steps {
                sh 'ls'
            }
        }
        
        stage('list files') {
            steps {
                sh 'python3 my_py.py'
            }
        }
    }
}
