pipeline {
    agent any
    stages {
        stage('Run Ansible Playbook') {
            steps {
                script {
                    sh '/usr/bin/ansible-playbook -i /etc/ansible/hosts deploy-web.yml'
                }
            }
        }
    }
}
