node {
  stage('SCM checkout') {
    git 'https://amandeep1410:%40Amandeeps14@github.com/amandeep1410/test_repo.git'
  }
  stage('Compile and build'){
    def mvnHome = tool name: 'maven_3', type: 'maven'
    sh '${mvnHome} mvn package'
  }
}
