pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
      git url:"https://github.com/Jnyanesh/jenkins-lab-test.git",
        branch:'main'
    }
  }
  stage('run script'){
    steps{
    sh "chmod +x script.sh"
    sh "./script.sh"
  }
}
  }
}
    
    
      
