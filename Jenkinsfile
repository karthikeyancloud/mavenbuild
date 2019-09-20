pipeline {
  agent any
  stages {
    stage('Git') {
      steps {
        git(url: 'https://github.com/karthikeyancloud/maven', branch: 'master', credentialsId: '82270236-0d23-492b-9f6d-1a7e82639b35')
      }
    }
  }
}