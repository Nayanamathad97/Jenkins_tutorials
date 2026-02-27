pipeline
{
    agent any

    stages
    {
        stage('STAGE')
        {
            steps
            {
                echo "This is STAGE1"
                sh ''' pwd
                   ls -lrt '''

            }
        }
        stage('STAGE2')
        {
            steps
            {
                echo "This is STAGE2"
            }
        }
    }
}