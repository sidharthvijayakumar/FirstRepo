node{
  stage('SCM Checout'){
   
  git 'https://github.com/sidharthvijayakumar/FirstRepo'
  }
  stage('Comiple-Package'){
     def mvnHome = tool name: 'Maven', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
