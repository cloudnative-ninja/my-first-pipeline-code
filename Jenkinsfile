pipeline {
    agent any
    stages {
        stage ('stage-1') {
            steps {
                echo "This is my first step in the stage-1"
            }
        }
        stage ('stage-2') {
            steps {
                echo "This is my first step in the stage-2"
            }
            {
                echo "This is my second step in the stage-2"
            }
        }
        stage ('stage-3') {
            steps {
                echo "This is the first step in stage-3"
            }
        }
    }
}
