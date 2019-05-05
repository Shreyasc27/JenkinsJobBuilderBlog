# Jenkins Job Builder - Step by Step Guide


### Steps - 


1. Clone the repository - `git clone https://git.openstack.org/openstack-infra/jenkins-job-builder`

2. `cd jenkins-job-builder`

3. Copy the folder - `etc` and `jobs` into `jenkins-job-builder`

4. Execute the commands in jenkins-job-builder folder

	a. Create **Single Job** - `jenkins-jobs --conf etc/jenkins_jobs.ini update jobs/singlejob.yaml`

	b. Create **Single Job from Template** - `jenkins-jobs --conf etc/jenkins_jobs.ini update jobs/singlejobtemplate.yaml`

	c. Create **Multiple Jobs from Template** - `jenkins-jobs --conf etc/jenkins_jobs.ini update jobs/multiplejobtemplate.yaml`

