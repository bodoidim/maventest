pipeline{
agent any
  stages{
    stage('printsomething'){
      when{
      changelog 'Build'
      }
      steps{
        echo "MESSAGE PRINT"
      }
    }
    stage('deploy stage'){
      when{
      changelog 'Deploy'
      }
      steps{
        echo "this stage will use for deploy"
      }
    }
  }
}
