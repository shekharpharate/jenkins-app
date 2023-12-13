pipeline {
    
    agent any 
    
    stages {
        
        stage ("stage-1")  {
            
            steps {
                
                sh "yum install httpd -y"
                sh "service httpd on"
                sh "chkconfig httpd start"
                sh "cp /root/.jenkins/workspace/jenkins-job/index.html /var/www/html"
                sh "cd /"
                sh "chmod -R 777 /var "
                
            }
        }
        
    }
    
}
