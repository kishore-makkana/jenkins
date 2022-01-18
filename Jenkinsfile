pipeline {
    agent {
        label 'master'
    }

    stages {
        stage("A") {
            options {
                timeout(time: 5, unit: "SECONDS")
            }

            steps {
                echo "Started stage A"
                sleep(time: 15, unit: "SECONDS")
            }
        }
    }
}
