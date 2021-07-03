pipeline {
    agent any
    stages {
        stage ('First Stage') {
            steps {
                echo "This is my first step in the stage-1"
            }
        }
        stage ('Second Stage') {
            steps {
                echo "This is my first step in the stage-2"
            }
            {
                echo "This is my second step in the stage-2"
            }
        }
        stage ('Third stage') {
            steps {
                echo "This is the first step in stage-3"
            }
        }
    }
}
