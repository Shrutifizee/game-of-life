pipeline
{
	agent any
	stages
	{
		stage ('nuget restore')
		{
			steps
			{
				sh "echo hello"
			}
		}
		stage ('Code build')
		{
			steps
			{
				sh "echo hello"
			}
		}
		stage ('Release artifact')
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
