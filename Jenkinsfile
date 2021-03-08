node {
  stage('SCM checkout') {
    git 'https://github.com/Rakhee99/clone-check'
  }
  stage ('compile Package') {
    sh 'mvn package'
  }
}
