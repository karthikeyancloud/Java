pipeline {
  agent any
  stages {
    stage('Git_check') {
      steps {
        git(url: 'https://github.com/karthikeyancloud/Java', branch: 'master', credentialsId: '8de3a359-9072-40f7-bf8d-3fbcb2274117')
      }
    }
  }
}