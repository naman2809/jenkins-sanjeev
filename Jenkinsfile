node{
stage ('scm checkout'){
git 'github.com/naman2809/jenkins-sanjeev'
}
stage ('compile-package'){
  //Git maven home path
  def mvnHome = tool name: 'maven-3', type: 'maven'
  sh "$(mvnHome)/bin/mvn"
}

}
