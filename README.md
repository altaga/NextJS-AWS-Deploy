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

Para mas detalles sobre el framework Serverless.

https://www.serverless.com/blog/serverless-nextjs

Para mas Detalles de NextJS API:

https://nextjs.org/docs/api-routes/introduction
  
Y listo. :3
  
