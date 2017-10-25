node() {
  stage ('Extract') {
    parallel 'Extract':{
      dir('project1') {
        git url: 'https://github.com/ahedevops/sandbox.git', credentialsId: '78953c3a-17ba-4a2a-a631-6a9ffc90fe0b'
      }
      dir('project2') {
        git url: 'https://github.com/ahedevops/XitJS.git', credentialsId: '78953c3a-17ba-4a2a-a631-6a9ffc90fe0b'
      }
    }   
  }
}
