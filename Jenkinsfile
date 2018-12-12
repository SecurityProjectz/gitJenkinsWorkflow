pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'initializing'
      }
    }
    stage('git') {
      steps {
        git(url: 'https://github.com/SecurityProjectz/gitJenkinsWorkflow.git', branch: 'develop', changelog: true)
      }
    }
  }
}