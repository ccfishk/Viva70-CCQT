pipeline {
  agent any
    parameters {
    booleanParam(
    name:"AAA",
    defaultValue:true,
    description: "CheckBox parameter")
    String(
    name:"BBBB",
    defaultValue:"Need a Path",
    description: "Want to dance")
    }
stages{
    stage('Example') {
    steps {
      echo "Hello world"
      echo "trying ${params.AAA}"
        }
}
        
  }
}
}
