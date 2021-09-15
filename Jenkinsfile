node {
    stage('Init') {
    sh "/opt/gradle/gradle-6.4.1/bin/gradle init"
    }
  stage('BUILD') {
    sh "/opt/gradle/gradle-6.4.1/bin/gradle build"
  }
  stage('TEST') {
    sh "/opt/gradle/gradle-6.4.1/bin/gradle build test"
  }
  stage('CLEAN') {
    sh "/opt/gradle/gradle-6.4.1/bin/gradle build clean"
  }
}
