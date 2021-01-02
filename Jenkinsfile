pipeline{
  agent any
  stages{
    stage('try to get python env'){
      steps{
        withPythonEnv('/Users/mac/.virtualenvs'){
          sh 'workon uitest_env_3.7.9'
          sh 'pip list'
         
        }
      }
    
    }
  }

}
