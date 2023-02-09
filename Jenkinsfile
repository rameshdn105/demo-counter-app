pipeline {
    agent any
    stages{
        stage('Git checkout'){
        steps{
            git branch: 'main', url: 'https://github.com/rameshdn105/demo-counter-app.git'
        }
    }
          stage('Unit testing'){
              steps{
                  sh 'mvn test'
              }
          }
    }
}
