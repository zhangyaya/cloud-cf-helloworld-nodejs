@Library('piper-lib-os') _

agent any

node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }

    stage('build') {
        mtaBuild script: this
}

}