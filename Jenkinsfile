node{
stage('SCM Checkout'){
git'https://github.com/mamatha-eng/testing'
}
stage('Compile-package){
def mvnhome= tool name: 'maven-3', type " 'maven'
sh "${mvnHome}/bin/mvn package"
}
}
