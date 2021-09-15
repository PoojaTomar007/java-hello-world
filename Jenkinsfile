node {
  stage('BUILD') {
    sh "chmod -R 755 gradlew"
    sh "/opt/gradle/gradle-6.4.1/bin/gradle build"
  }
  stage('TEST') {
    sh "/opt/gradle/gradle-6.4.1/bin/gradle build test"
  }
  stage('CLEAN') {
    sh "/opt/gradle/gradle-6.4.1/bin/gradle build clean"
  }
}
