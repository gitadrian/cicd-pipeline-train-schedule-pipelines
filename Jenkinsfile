pipeline{
  agent any
  
  stages{
    stage('Build'){
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip' 
    }
  }
}
