pipeline{
    agent any
    stages {
        stage(building node){
            steps {
                echo 'building node'
                nodejs('NodeJS15.14'){
                    bat 'npm install'
                }
            }
        }
    }
}
