    node {
    	stage ('scm checkout'){
    	  
    	   git 'https://github.com/devarampatisrikanth/maven-project'
    	}
    	stage ('mvn package'){
    	def mvn_home = tool name: 'm2_home', type: 'maven'
    	sh "${mvn_home}/bin/mvn package"
    	}
    }
