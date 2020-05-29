stage 'Build'
node {
    tool name: 'Java', type: 'jdk'
    tool name: 'Maven', type: 'maven'
    checkout scm

    bat 'cmd.exe /C "mvn clean compile && exit %%ERRORLEVEL%%"'

}
