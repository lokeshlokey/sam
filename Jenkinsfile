pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac Class1.java """
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ java Class1 """
				}
			}
			
		}
	}
