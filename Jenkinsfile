pipeline {

  agent any

  stages {

    stage('Checkout SCM') {
     steps {
				git 'https://github.com/wupti123/CICD_Front-master.git'
			}
}
   stage('build'){
    steps {

          script{

          sh "ansible-playbook ansible/build.yml -i ansible/inventory/host.yml"
}


}
}


  }

}
