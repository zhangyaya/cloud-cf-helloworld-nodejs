@Library('piper-lib-os') _

node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
    stage('build') {
        mavenBuild script: this
    }
 
}