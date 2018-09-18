    node {
    	stage ('scm checkout'){
    	  
    	   git 'https://github.com/devarampatisrikanth/maven-project'
    	}
    	stage ('mvn package'){
    	def mvn_home = tool name: 'M2_HOME', type: 'maven'
    	sh "${mvn_home}/bin/mvn package"
    	}
    }
