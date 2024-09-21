pipeline
{
  agent any
  stages
  {
    stage('scm checkout')
    { steps{ "git branch: 'main', url: 'https://github.com/shubhu34/devops_pipeline_jenkins.git'" }}
    
    stage('print your message')
    {      steps{ sh 'echo hello'} }
  }
}
