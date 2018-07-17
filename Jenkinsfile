node ('master'){
  stage ('scm checkout'){
  git 'https://github.com/devarampatisrikanth/maven-project'
  }
  stage ('compile-package'){
    //getting mvn path
   def mvnhome=tool name: 'm2_home', type: 'maven'
    sh "${mvnhome}/bin/mvn package"
  }
}
