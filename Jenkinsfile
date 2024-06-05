node {
    stage('git checkout') {
    git ' https://github.com/nithingowdahm87/maven-test.git'
    }
    stage('build') {
    sh 'mvn clean install'
    }
