pipeline {
  agent any
  stages {
    stage('Gitclone') {
      steps {
        git(url: 'https://github.com/karthikeyancloud/mavenbuild', branch: 'master', credentialsId: '27a0381d-c6bd-495e-8d06-84cfbc6430fb')
      }
    }
    stage('Build') {
      steps {
        sh '''dir /opt/bitnami/apps/jenkins/jenkins_home/workspace/mavenbuild_master 

'''
        echo 'Starting Build'
      }
    }
  }
}