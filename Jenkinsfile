node {
  stage('Checkout SCM') {
    git 'https://github.com/madhunivi555/god-7.git'
  }
  stage('Compile Package') {
    def mvnHome = tool name: 'maven_3_6_2', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }  
}
