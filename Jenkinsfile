node{
stage ('scm checkout'){
git 'https://github.com/naman2809/jenkins-sanjeev.git'
}
stage ('compile-package'){
  //Git maven home path
  def mvnHome = tool name: 'maven-3', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}

}
