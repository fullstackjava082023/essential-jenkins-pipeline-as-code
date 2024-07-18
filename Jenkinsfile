pipeline {
    agent any
    options {
        buildDiscarder(logRotator(daysToKeepStr: '10', numToKeepStr: '10'))
        timeout(time: 12, unit: 'HOURS')
    }
    stages {
        stage("Hello!\nPlease read the logs.") {
            steps {
                echo "VERSION 2"
                echo "Hello! Thanks for visiting the Jenkins Essential Training repo on GitHub.\n\nIf you are working with the exercise files and see this message you are good!"
                echo "The link to jenkisfile: https://github.com/fullstackjava082023/essential-jenkins-pipeline-as-code/blob/main/Jenkinsfile"
            }
        }
    }
}

