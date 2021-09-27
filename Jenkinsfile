node{
  stage('SOM Checkout'){
    git 'https://github.com/ravindra1234567/mavenmvc'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: '', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
