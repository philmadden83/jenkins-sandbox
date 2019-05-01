node {
  stage("test") {
    checkout scm
    def f = load 'funcs.groovy'
    f.x()
  }
}

def x() {
  println "Hello, world from pipeline"
}
