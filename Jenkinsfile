pipeline {
    agent any
    environment{
	  CC='CLANG'
	}
    stages {
        stage('Example') {
            steps {

                echo "Running a b ${env.BUILD_ID} on ${env.JENKINS_URL}"
		sh 'printenv'

            }
        }
    }
}
