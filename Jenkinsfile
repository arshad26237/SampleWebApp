pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Assuming your build.xml file is at the root of the Jenkins workspace
                // Adjust the path if your build.xml is in a different location
                sh 'ant -f build.xml'
            }
        }
    }
}
