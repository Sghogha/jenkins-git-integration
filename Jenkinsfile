pipeline{
  agent any 
  stages {
  stage('maven install') {
    steps {
       withMaven(maven: 'maven3') {
           sh 'clean install'
}
    }
  }

}
}
