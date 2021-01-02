pipeline{
  agent any
  stages{
    stage('try to get python env'){
      steps{
         withPythonEnv('/Users/mac/.virtualenvs/uitest_env_3.7.9/bin/python'){
          sh 'pip -V'
          sh 'python -m pip install --upgrade pip'
        }
      }
      steps{
          sh 'pip -V'
          sh 'pip install -r requiments'
          sh 'python openWebSite.py'
      
      }
    
    }
  }

}
