#!groovy
//nodeJS Jenkinsfile
node{
  sh('ls -l')
}
def pipeline = fileLoader.fromGit('nodejs-pipeline', 'https://csp-github.sam.gov/GSA-IAE-Infrastructure/pipeline.git', 'master', 'prod-github-cred', '')
pipeline.start()
