pipeline {
    agent any
    environment {
        x = '100'
    }
	parameters {
		string(name: "person", defaultValue: "Ekamjeet Singh", description: "Enter username")
	}
    stages {
        stage('Hello') {
            steps {
                sh 'date'
				sh 'echo $x'
            }
        }
		stage('Check Paramters') {
            steps {
                sh 'echo $person'
				
            }
        }
    }
}
