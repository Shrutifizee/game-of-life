pipeline
{
	agent any
	stages
	{
		stage ('checkout')
		{
			steps
			{
				sh "echo hello"
			}
		}
		stage ('Build')
		{
			steps
			{
				sh "echo hello"
			}
		}
		stage ('Unit Testing')
		{
			steps
			{
				sh "echo hello"
			}
		}
		stage ('Upload to Artifactory')
		{
			steps
			{
				sh "echo hello"
			}
		}
		stage ('Docker Image')
		{
			steps
			{
				sh "echo hello"
			}
		}
		stage('Containers') 
		{
			steps 
			{
				parallel(
					PushtoDTR: 
					{
						sh "echo hello"
					},
					PrecontainerCheck: 
					{
						sh "echo hello"
					}
				)
			}
		}
		stage ('Docker deployment')
		{
		    steps
		    {
		        sh "echo hello"
		    }
		}
		stage ('Helm Chart Deployment')
		{
		    steps
		    {
		        sh "echo hello"
		    }
		}
	}
}
