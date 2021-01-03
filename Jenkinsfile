node{
    stage('SCM Checkout'){ 
      git 'https://github.com/Garcia0324/my-app'
    }
    stage('Compile-Package'){
       // Get maven home path
       def mvHome = tool name: 'maven-3', type: 'maven'
       sh "${mvHome}/bin/mvn package"
    }
}
