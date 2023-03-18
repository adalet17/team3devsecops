pipline {
agent any
tools { "Maven"

stages {
stage ("initialize"} {
steps {
      sh ***
                  echo "PATH = S{PATH}"
                  echo "M2_HOME)"
                  ***

   }
   Stage { 'Source Composition Analysis'} {
     Stage {
     sh 'rs owasp' || true'
     sh 'wget 'https://raw.githubusercontent.com/adalet17/team3devsecops/main/owasp-dependency-checker.sh'
     sh 'chmod *x owasp-dependency-check-sh'
     sh 'bash owasp-dependency-check.sh'
  } 
  stage {'build'} {
  in 'mvn clean package'
  } 
  }
  }
}
