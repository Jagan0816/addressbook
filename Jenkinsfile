pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'Compiling the code'
            }
        }
        stage('CodeReview') {
            steps {
                echo 'Reviewing the code with pmd'
            }
        }
        stage('UnitTest') {
            steps {
                echo 'Testing the code with junit'
            }
        }
        stage('CoverageAnalysis') {
            steps {
                echo 'Static code coverage with jacoco'
            }
        }
        stage('Package') {
            steps {
                echo 'Packaging the code'
            }
        }
        stage('Publish') {
            steps {
                echo 'Publishing the artifact to jfrog'
            }
        }
    }
}
