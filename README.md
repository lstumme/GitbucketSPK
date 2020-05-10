# GitbucketSpk

[GitBucket](https://github.com/gitbucket/gitbucket)  is a GitHub clone powered by Scala which has easy installation and high extensibility.

GitbucketSpk is a GitBucket packaged for Synlogy NAS.

GitBucketSpk packages the gitbucket.war file from https://github.com/gitbucket/gitbucket into a spk-package for installation in the Synology NAS.

GitBucketSpk is based on [GitBucket.for.Synology](https://github.com/breuniga/GitBucket.for.Synology) project which seems no to be maintained anymore.

As a result GitBucketSpk works with DSM6.0 and above.


# GitBucket's license

see https://github.com/takezoe/gitbucket


# Installation

GitBucket requires Java installed on the Synology NAS. You can install Java8 via the Java Manager from Synology Inc.
You also have to create a directory for Gitbucket Repository (for exemple : /volume1/gitbucket/data).
1) Download the latest [release](https://github.com/despeludo/GitbucketSpk/releases/download/v1.0-DSM6-4.19.3/GitBucket.spk)
2) Login to your Synology NAS with administrator rights
3) Open the Package Manager
4) Click on Manual Install and select the downloaded package.
5) Provide information for git repository path location and GitBucket Server port (8090 by default) 
    
When installation is completed, you can access GitBucket via the Synology Main Menu or directly by http(s)://yourNAS:8080
