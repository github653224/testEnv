pipeline{
  agent any
  stages{
    stage('try to get python env'){
      steps{
         withPythonEnv('/Users/mac/.virtualenvs/uitest_env_3.7.9/bin/python'){
          sh 'pip list'
          sh 'pip -V'
          sh 'python -m pip list'
          sh 'pwd'
          
         
        }
      }
    
    }
  }

}
