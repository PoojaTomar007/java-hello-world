node{
   stage 'build_Project'
  if(isUnix()){
  sh '/opt/gradle/gradle-6.4.1/bin/gradle init'
  }
  stage 'build_Project'
  if(isUnix()){
  sh '/opt/gradle/gradle-6.4.1/bin/gradle test'
  }
  stage 'build_Project'
  if(isUnix()){
  sh '/opt/gradle/gradle-6.4.1/bin/gradle build'
  }
}
