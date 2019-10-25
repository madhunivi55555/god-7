node {
  stage('Checkout SCM') {
    git 
  }
  stage('Compile Package') {
    def mvnHome = tool name: 'maven_3_6_2', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }  
}
