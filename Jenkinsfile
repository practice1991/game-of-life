pipeline{
    agent { label 'REDHAT' }
stages{
    stage('Source')
    steps{
        git 'https://github.com/practice1991/game-of-life.git'
    }
}
stage('Package'){
    steps{
        sh 'mvn package'
    }
}
}