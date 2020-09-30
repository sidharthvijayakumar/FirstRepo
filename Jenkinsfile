node{
  stage('SCM Checout'){
    tool name: 'Maven', type: 'maven'
  git 'https://github.com/sidharthvijayakumar/FirstRepo'
  }
  stage('Comiple-Package'){
    sh 'mvn package'
  }
}
