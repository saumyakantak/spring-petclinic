pipeline {
    agent any

    stages {
        stage('Echo Message') {
            steps {
                echo 'Hello World!!'
                echo "Build No. : $BUILD_NUMBER"
                script{
                    print("in Script Block")
                }
            }
        }
    }
}
