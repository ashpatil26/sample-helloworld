stage 'Build'
node {
    tool name: 'Java', type: 'jdk'
    tool name: 'Maven', type: 'maven'
    checkout scm

    bat 'cmd.exe /C "mvn clean install && exit %%ERRORLEVEL%%"'

}

stage 'Test"
node {
    bat 'mvn test'
    
}    
