node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/Punchcoco/jenkins.git'
    }
    stage('Build') {
        sh 'javac main.java'
    }
    stage('run') {
        sh 'java HelloWorld'
    }
}
