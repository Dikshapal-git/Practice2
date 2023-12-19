Pipeline{
         agent any
         stages{
         stage('checkout')
         Steps{
               checkout SCM
              }  
             }
         stage('Build'){
         Steps{
                sh'/home/diksha-1/Documents/ExtractFile/apache-maven-3.9.3/mvn install'
              }
                       } 
         stage('Deployment')
         {  
           Steps
           { 
                sh 'cp target/Practice2.war /home/diksha-1/Documents/ExtractFile/apache-tomcat-9.0.80/webapp'
                }
         }
        }
