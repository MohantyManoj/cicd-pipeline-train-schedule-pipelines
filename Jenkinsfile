pipeline {
 agent any
 stages {
   stage ('Build')
   {
    Steps {
    echo 'Running Build Automation'
    sh './gradelw build --no-daemon'
    archieveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
   
   }
 
 }
}
