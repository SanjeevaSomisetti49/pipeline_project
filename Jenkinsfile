pipeline
        {
        agent any
        stages
                {
                stage("Git")
                        {
                        steps
                                {
                                git "https://github.com/SanjeevaSomisetti49/pipeline_project.git"
                                }
                        }
                stage("Run")
                        {
                        steps
                                {
                                sh "java Demo.java"
                                }
                        }
		stage("Run")
			{
			steps
				{
				sh "python3 main.py"
				}
			}
		}
	}
