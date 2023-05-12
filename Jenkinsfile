pipeline {
    agent any

    stages {
        stage('clone repo') {
            steps {
                bat "git clone https://github.com/gowtham-it21/dayskill2.git"
		bat "mvn clean -f dayskill2"
            }
        }
        stage('Test') {
            steps {
               bat "mvn clean -f dayskill2"
            }
        }
	stage ('Deploy'){
		steps {
		    bat "mvn clean -f dayskill2"
}
}
   
    }
}
