node
{
    stage('SCP source file') {
        sshagent(['ssh-agent']) {
            sh 'scp -r /var/lib/jenkins/workspace/tomcat/*.war ubuntu@13.236.153.82:/var/lib/tomcat9/webapps'
        }
    }
}
