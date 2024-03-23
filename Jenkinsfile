pipeline{
  agent {
    label 'MCU_DEVELOPMENT3_CELL'
  }
  tools{
    matlab 'R2022b'
  }
  stages{
    stage('Test'){
      runMATLABCommand("ver")
    }
  }
}
  
