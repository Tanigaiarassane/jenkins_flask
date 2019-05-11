pipeline{
agent any
    stages{
    stage ("git clone")
        {
         git 'https://github.com/Tanigaiarassane/jenkins_flask.git'     
        }
        stage("Buid image"){
              sh 'docker build -t my-flask-image:latest .'
      
        }
    }
}
