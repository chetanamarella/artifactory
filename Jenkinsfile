pipeline {
 
 tools {
  maven 'mymaven'
  jdk 'myjdk'
 }
 stages {
  stage('Cloning git') {
   steps {
    git 'https://github.com/chetanamarella/simple-java-maven-app.git'
   }
  }
  
  /*stage('Maven build') {
   steps {
    sh 'mvn clean install'
   }
  }
  
  stage('Push jar to artifactory') {
   steps {
    rtUpload (
     serverId: 'Artifactory-server',
     spec: '''{
       "files": [
          {
            "pattern": "/var/lib/jenkins/workspace/artifactory/target/*.jar",
            "target": "chetana/"
          }
         ]
     }'''
    )
   }
  }*/
 }
}
  
  
   
