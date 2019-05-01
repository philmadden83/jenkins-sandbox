node {
  stage("test") {
    checkout scm
    load 'funcs.groovy'
    x()
  }
}

def x() {
  println "Hello, world from pipeline"
}
