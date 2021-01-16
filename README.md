# ci-travis

CI with Travis. Each "git push" triggers: 
- A deploy job on a clean new environment (local pc ---> Travis server). 
- A deploy to the AWS cloud via the serverless framework (Travis server ---> AWS cloud).  
