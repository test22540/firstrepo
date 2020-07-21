pipeline {
     agent any
    stages {
        stage('Git checkout') {
            steps {
                git branch: 'secondrepo', credentialsId: '5c67fae8-a1ba-48f4-a0f3-f2b2625f7ab7', url: 'https://github.com/test22540/firstrepo.git'
            }
             stage('Maven build')
             {
                  steps{
          sh "mvn clean package"
        }
    }
}
    }
}
