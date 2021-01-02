pipeline{
  agent any
  stages{
    stage('try to get python env'){
      steps{
        withPythonEnv('/Users/mac/.virtualenvs/uitest_env_3.7.9/bin/python3'){
          sh 'workon uitest_env_3.7.9'
          sh 'pip list'
         
        }
      }
    
    }
  }

}
