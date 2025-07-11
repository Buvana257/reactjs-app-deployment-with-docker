pipeline {
    agent any

    stages {
        stage ('changing the file permission') {
            steps {
                echo "Making build.sh executable..."
                sh ' chmod +x build.sh'
            }
        }

        stage ('executing the file') {
            steps {
                echo "Running build.sh script..."
                sh './build.sh'
            }
        }
    }
}
