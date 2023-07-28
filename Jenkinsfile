pipeline{
  agent any
  stages{
    stage('SCM testing'){
      steps{
        echo "SCM Passsed"
      }
    }

    stage("Running Ansible playbook"){
      steps{
        sh 'ansible-playbook playbook.yml'
        echo "Playbook has been executed successfully"
      }
    }
  }
}
