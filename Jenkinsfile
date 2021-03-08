node {
  stage('SCM checkout') {
    git 'https://github.com/Rakhee99/clone-check'
  }
  stage ('compile Package') {
    // get maven home
    def mvnhome = tool name: 'MAVEN-R', type: 'maven'
    sh "${mvnhome}/bin/package"
  }
}
