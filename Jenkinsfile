node {
    stage('Clone') {
        git 'https://github.com/remiliance/playbookansible.git'
    }
    stage('Ansible') {
    sh 'ansible-playbook -i hosts.ini playbook.yml'
    }
}
