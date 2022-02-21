node {
    stage('clone') {
        git 'https://github.com/hamelito/Jenkins-helloworld.git'
    }
    
    stage('buid') {
        sh label:'', script: 'javac Main.java'
    }
  
    stage('run') {
        sh label:'', script: 'java Main'
    }    
}

