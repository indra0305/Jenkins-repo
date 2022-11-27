
			//this is for env variables
			pipeline{
				agent any
				
				environment{
					NAME = "Indra"
					PLACE = "PUNE"
				}
				
				stages{
					stage("env-var"){
						steps{
							echo "${NAME}"
							echo "${PLACE}"
						}
					}
				}
			}
