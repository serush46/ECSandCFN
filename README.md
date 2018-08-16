# Provisioning and CI/CD of ECS containers with Cloudformation and Codepipeline                                        
# Architecture              
  ![alt text](https://raw.githubusercontent.com/serush46/ECSwithCFN/master/arch.png)            

Create a Codepipeline with                  
**Source** stage as: Github/Codecommit (refer: sample.war)                                  
**Build** stage as: Codebuild (refer: buildspec.yml, Dockerfile)                                       
**Deploy** stage as: Cloudformation (ECS) (refer: ecs.json)                                          

Note: You should have basic understanding on Codepipeline, ECS and intermediate knowledge on Cloudformation to understand this template.
