pipeline {
  agent any
  stages {
        stage('Stage 1') {
            steps {
                sh "echo 1"
            }
        }
        stage('Stage 2') {
            steps {
                script {
                    pullRequest.comment('This PR is highly illogical..')
                }
            }
        }
    }

}
