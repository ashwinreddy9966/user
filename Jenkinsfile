@Library('roboshop-shared-library@main') _

pipeline {
agent any
    stages {
        stage('Lint Checks'){
        steps {
        script { nodejs.lintCheck('user') }
           }
        }
    } // end of stages
}