# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

- VM is more expensive to run in comparison to App service. App service do not offer Pay-as-you-Go but we can shutdown VM when not use to save cost.
- App service have constrains in comparison to VM in term of scalability(eg: programming languages) 
- The development of app is much simpler and faster in App service
- VM offer developer more control over the enviroments and allow for more customization of the app's capability but App service very useful for teams with less manpower, and less experience with managing hardware 

- I have chosen App service for deploying the app

- Reason : 
    + This app is very lightweight and no need to use VM.
    + Using Python language that supported by App service
    + Support continous deployment through Github workflows 
    + No need to offer Pay-as-you-Go
    + Security control over by Azure
    + Easy to deploy

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

Requirement : The application become more bigger that would require more hardware and need take more control over the enviroment.

Solution : To use VM for deployment. Required more hardware which can increase costs. Managing and deployment are also complex but can meet the requirement.