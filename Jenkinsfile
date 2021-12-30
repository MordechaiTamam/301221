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
        
        stage('Run my_py') {
            steps {
                sh 'python3 my_py.py'
            }
        }
    }
}
