pipeline{
  agent any 
  environment {
    JAVA_HOME = "/usr/bin/java"
  }
  parameters{
    choice choices: ['dev','sit','pt','prod'], name: 'ENV'
  }
  parameters {
  choice choices: ['v1', 'v2', 'v3', 'v4'], name: 'version'
}
  stages{
   stage('welcome note'){
    steps{
    script{
      subject="jenkinspac"
      println "Value of subject is ${subject}"
      println "Welcome to jenkins pipeline scripting"
      println "my workspace is ${WORKSPACE}"
      println "MY BUILD NO IS ${BUILD_NUMBER}"
      println "MY java home path is ${env.JAVA_HOME}"
      println "my env values is ${params.ENV}"
      }
     }
    }
  }
}
