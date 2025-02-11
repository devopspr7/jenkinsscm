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
        stage ('dockerbuild') {
            steps {
                echo "Executing Docker build"
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
