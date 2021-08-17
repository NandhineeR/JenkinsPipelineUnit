#!groovy

def deployBranches = [ "master" ]
def phase = "verify"

stage ('Build') {
   node {
  withGradle {
    sh './gradlew build'
  }
}
}
