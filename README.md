Catpipeline is a full pipeline project to create CI/CD for a highly available application. Whenever a new commit is added to the repository, AWS CloudWatch Events triggers for the pipeline to update and deploy an updated application. The application is ran on 2 containers, each in a different available zone that are part of the target group configured in the Application Load Balancer.
![Screenshot_3](https://user-images.githubusercontent.com/109190196/214722186-f116269e-0e78-4bb2-9471-b3315a3c516c.jpg)
![Screenshot_1](https://user-images.githubusercontent.com/109190196/214722239-0c3f5a3c-adb8-46f6-8a98-1eeb53ad8199.jpg)
![Screenshot_4](https://user-images.githubusercontent.com/109190196/214722253-271f5204-4a22-4882-b2ec-23182a4f6a43.jpg)
