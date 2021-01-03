node{
    stage('SCM Checkout'){
        git 'https://github.com/Garcia0324/my-app'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}
