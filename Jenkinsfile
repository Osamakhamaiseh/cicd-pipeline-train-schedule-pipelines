Pipeline{
  agent any
  Stages{
    Stage('Build'){
      Steps{
        echo 'Running Build Automation' 
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts : 'dist/trainSchedule.zip'
      }
   }
  }
}
