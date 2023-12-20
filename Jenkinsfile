Pipeline {
        agent any
        stages {
                 stage('Checkout') {
                    Steps {
                    checkout scm
                    } }
                 stage('Build'){
                     Steps{
                     sh '/home/diksha-1/Documents/ExtractFile/apache-maven-3.9.3/mvn install'
                     }}   
                 stage('Deployment') {
                      Steps{
                      sh 'cp target/Project1.war /home/diksha-1/Documents/ExtractFile/apache-tomcat-9.0.80/webapps'

                      }}   
                    }
        }
        
