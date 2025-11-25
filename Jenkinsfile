pipeline {
    agent any
     stages {
        stage ('GIT Pull stage')
        {
            steps {
            git url: 'https://github.com/praveenm7985/simple-java-maven-app.git'
                  }
        }

        stage ('Deploy step start')

        {
            steps {
            bat 'mvn package'
                  }
        }
     }
}
