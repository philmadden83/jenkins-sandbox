node {
  stage("test") {
    checkout scm
    def f = load "${env.WORKSPACE}/funcs.groovy"
    f.x()
  }
}

def x() {
  println "Hello, world from pipeline"
}
