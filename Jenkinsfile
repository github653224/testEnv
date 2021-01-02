pipeline{
  agent any
  stages{
    stage('try to get python env'){
      steps{
        withPythonEnv('$HOME/.virtualenvs'){
          sh 'workon uitest_env_3.7.9'
          sh 'pip list'
         
        }
      }
    
    }
  }

}
