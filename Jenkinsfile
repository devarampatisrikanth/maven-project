node ('master'){
  stage ('scm checkout'){
  git 'https://github.com/devarampatisrikanth/maven-project'
  }
  stage ('compile-package'){
  sh 'mvn package'
  }
}
