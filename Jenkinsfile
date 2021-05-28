pipeline {
  agent any

  parameters {
    gitParameter branch: 'master', branchFilter: '.*', defaultValue: '', name: 'TAG', quickFilterEnabled: true, selectedValue: 'TOP', sortMode: 'DESCENDING_SMART', tagFilter: '*', type: 'PT_TAG'
  }

  stages {
    stage('test') {
      steps {
        echo "test ${params.TAG}"
      }
    }
  }
}
