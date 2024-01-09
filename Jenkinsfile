node
{
    stage('SCP source file') {
        sshagent(['ssh-agent']) {
            sh 'scp -r /var/lib/jenkins/workspace/pipeline/* ubuntu@13.236.153.82:/var/www/html'
        }
    }
}
