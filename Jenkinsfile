pipeline{
agent any
  stages{
    stage('pl_script_detect'){
      when{
      changeset '*.pl'
      }
      steps{
        echo "PL DETECTED"
      }
    }
    stage('whenxml'){
      when{
      changeset '*.xml'
      }
      steps{
        echo "xml detected"
      }
    }
  }
}
