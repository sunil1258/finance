node{
  stage('SCM Checkout'){
 git 'https://github.com/sunil1258/finance'
 }
 stage('Compile-Package'){
   def mvnhome= tool name: 'maven', type: 'maven'
   sh "${mvnhome}/bin/mvn package"
 }
}
