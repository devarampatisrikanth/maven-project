node ('master'){
  stage ('scm checkout'){
  git 'https://github.com/devarampatisrikanth/maven-project'
  }
  stage ('compile-package'){
    //getting mvn path
   def mvnhome=tool name: 'maven-3', type: 'maven'
    sh "${mvnhome}/bin/mvn package"
  }
}
