pipeline
{
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
                sh'''
                sleep 10'''

            }
        }
    }
}