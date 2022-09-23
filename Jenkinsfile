pipeline {
    agent {} label 'master'}

    stages {

        stage('test') {
            steps {
                dir ("src/main")
                sh "mvn clean compile test"

            }
            
        }

        stage("build application") {
            steps {
                echo "WIP"
            }
        }

        stage("Create docker image") {
            steps {
                echo("WIP2")
            }
        }

    }
}