
pipeline {
  agent any
  triggers {
   cron('H/2 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger which was completed by me. Call me when you have a jenkins job'
	echo 'rene come lets study'
	echo 'jenkins webhook'
      }
    }

  }
}
