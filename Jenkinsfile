node {
    stage('clone') {
    git 'https://github.com/MaeBzh/jenkins-helloworld.git'
    }
    stage('build') {
        sh 'javac Main.java'
    }
    stage('run') {
        sh 'java Main'
    }
}
