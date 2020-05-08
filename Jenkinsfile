pipeline {
    agent {
        dockerfile true
    }
    stages {
        stage('Build') {
            steps {
                echo 'Hello World!'
		echo 'this is a test'
                sh 'echo myCustomEnvVar = $myCustomEnvVar'
            }
        }
    }
}
