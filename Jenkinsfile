node{
   stage('SCM Checkout'){
     git 'https://github.com/ouily1/repo2'
   }
   stage('Compile-Package'){
      def mvnhome = tool name: 'maven-3', type: 'maven'   
      "${mvnhome}/bin/mvn package"
   }
}