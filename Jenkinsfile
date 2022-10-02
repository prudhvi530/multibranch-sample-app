pipeline {
  agent {label 'master'}
  stages {
    stage('Build') {
      steps {
        script{
          sh "echo Hello 6"
          pullRequest.comment("Build ${env.BUILD_ID}")
        }
       }
      
    }
  }
}
