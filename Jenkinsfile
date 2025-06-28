pipeline {
    agent any
    stages {
        stage('Run Ansible Playbook') {
            steps {
                script {
                    sh 'ansible-playbook -i /etc/ansible/hosts deploy-web.yml'
                }
            }
        }
    }
}
