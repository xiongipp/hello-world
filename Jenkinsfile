

pipeline {

    parameters {
        choice(
            choices: ['all','gop-common-parent','hap','springboot-parent'],
            name: 'APPLICATION_NAME',
            description: 'please choose app to build , default is all-to-build'
        )
    }
    agent any

    stages {
        stage('Init') {
                steps {
                    echo "user choose param is ${params.APPLICATION_NAME}"
                    echo env.BRANCH_NAME
                    echo params.APPLICATION_NAME
                }
           }
        stage('打开冰箱') {
            steps {
                echo 'develop-2.0-Hello World'
            }
        }
        stage('装大象') {
            steps {
                echo 'develop-2.0-Hello World'
            }
        }
        stage('关冰箱') {
            steps {
                echo 'develop-2.0-Hello World'
            }
        }
    }
}