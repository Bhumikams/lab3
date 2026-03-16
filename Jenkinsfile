pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
        git url :'https://github.com/Bhumikams/lab3.git',
        branch :'main'
    }
  }
  stage('Run script'){
    steps{
      sh 'chmod +x script.sh',
        sh './script.sh'
     }
   }
  }
}
      
