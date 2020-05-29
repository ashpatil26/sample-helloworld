pipeline {
    tools {
        maven 'Maven'
        jdk 'Java'
    }

stage 'Build'
node {

    checkout scm

    bat 'mvn clean install'

}
}    

