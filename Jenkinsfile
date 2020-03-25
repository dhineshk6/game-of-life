node {
    stage ('git') {
        git 'https://github.com/dhineshk6/game-of-life.git'
   
    }
    stage ('build') {
        sh 'mvn clean package'
    }
}
