node {
    stage('actualizar codigo') {
      checkout scm
    }
	
	 stage('Construir') {
		if(isUnix()){
		  sh 'gradle build --info'

		  }
		  else{
			bat 'gradle build --info'
		  }
    }
}
	