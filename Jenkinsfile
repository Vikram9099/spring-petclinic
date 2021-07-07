node {
 
   stage('SCM') {
      // git clone
	  git 'https://github.com/GitPracticeRepo/spring-petclinic.git'
   }
   
   stage ('build the packages') {
      // mvn package
	  sh './mvnw package'
   }
 
   
   
   stage ('archival') {
     // archiving artifacts
	 archive 'target/*.jar'
   }
 
}
