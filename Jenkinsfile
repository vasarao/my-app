
node{
	stage('SCM Checkout'){
		git 'https://github.com/vasarao/my-app.git'
	}
	stage('Compile-Package'){
	  sh 'mvn package'
	}

}

