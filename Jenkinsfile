node{
  stage('SCM Checkout'){
    git 'https://github.com/MicroJava-Pradeep/project.git'
  }
  stage('Compile-Package'){
    // get maven package
    def MAVEN_HOME = tool name: 'C:\\Program Files\\Maven\\apache-maven-3.2.2-bin\\apache-maven-3.2.2\\bin', type: 'maven'
    sh "${mvnHOME}/bin/mvn package"
  }
}
