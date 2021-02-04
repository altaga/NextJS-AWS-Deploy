# NextJS-AWS-Deploy
Tutorial de como realizar un deploy de una NextJS App en AWS de forma Serverless

Pre-requisitos:
  - Cuenta en capa gratuita de AWS.
  - AWS CLI. https://aws.amazon.com/cli/
  - NodeJS. https://nodejs.org/es/
  - Serverless Framework. https://www.serverless.com/

  git clone https://github.com/altaga/NextJS-AWS-Deploy
  cd NextJS-AWS-Deploy
  npm run-script deploy
  npm install -g serverless
  
package.json
  
  "deploy": "npx serverless"
  
serverless.yml
  
  myNextApplication:
  component: "@sls-next/serverless-component"
  
Y listo. :3
  
