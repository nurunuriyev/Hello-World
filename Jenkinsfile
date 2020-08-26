pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo 'building the application...'
            }
        }
        stage("test") {
            steps {
                echo 'testing the application...'
            }
        }
        stage("deploy") {
            steps {
                echo 'deploying the application...'
                echo BRANCH_NAME
                echo JOB_BASE_NAME
                echo BUILD_TAG
                echo BUILD_URL
            }
        }
    }
}
