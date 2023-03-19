Pipeline {
  agent any
  stages {
    stage ('compile')
    steps {
      sh 'mvn clean compile'
    }
  }
  stage ('testing')
  steps {
    sh 'mvn test'
  }
}
stage ('install')
  steps {
    sh 'mvn install'
  }
}
stage ('branch')
  steps {
    echo 'This is master branch'
