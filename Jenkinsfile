pipeline {
    agent any 
    stages {
        stage ('Build') {
            steps {
                echo "Executing Multi branch pipeline from github"
            }
        }
        stage ('test') {
            steps {
                echo "Executing Test stage"
            }
        }
        stage ('deploytodev') {
            steps {
                echo "Executing Dev deployment stage"
            }
        }
        stage ('deploytoprod') {
            steps {
                echo "Executing Prod deployment stage"
            }
        }
    }
}
