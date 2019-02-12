node {
  stage('SCM checkout') {
    git 'https://amandeep1410:%40Amandeeps14@github.com/amandeep1410/test_repo.git'
  }
  stage('Compile and build'){
    sh 'mvn package'
  }
}
