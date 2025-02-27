node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/Fabien-adm/Jenkins_Pipeline.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    
    }
    stage('Run') {
        sh 'java Main'
    
    }
}
