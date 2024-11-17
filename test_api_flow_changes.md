## Flow Testing
I face a problem that every time I change a small thing in the backend, I need to check the full flow to ensure it doesn’t break anything here or there, 
and I need to check that everything works right. Here, I will list all solutions I will try one by one and say which ones work and in what cases they work for me

### 1. basic and working right now 
- write down the user story
- divide the user story into endpoints that do 1,2,3... 
- write the endpoint body and response before code the endpoint
- check the criteria and that it do the right behavior
- update the docs and explain everything you did and what you expect and how the response looks like

### Automate the basic flow
- after making sure that it works right and it matches the user story
- automate it use `superset` or any lib do this
- when any change happens to something related i rerun those tests and make sure it works as expected 
  
