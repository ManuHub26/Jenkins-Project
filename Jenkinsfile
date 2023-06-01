node {
    stage('Clone') {
        git 'https://github.com/ManuHub26/Jenkins-Project.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}