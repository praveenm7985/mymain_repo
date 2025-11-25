pipeline {
    agent any
     stages {
        stage ('GIT Pull stage')
        {
            steps { echo '****Git pull***'}
            git 'https://github.com/praveenm7985/simple-java-maven-app.git'
        
        }

        stage ('Deploy step start')

        {
            steps {echo '***Deploy stage started'}
            bat 'mvn clean package'
        }
     }
}
