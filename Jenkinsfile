pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload')
        {
            steps
            {
                git 'https://github.com/agehma/wed6july.git'
            }
        }
        stage('Continuousbuild')
        {
            steps
            {
                sh 'mvn package'
            }
        }
    }
}

