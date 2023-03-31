<h1 align="center" id="title">Serverless Application using AWS Services</h1>

<p id="description">The application architecture uses AWS Lambda Amazon API Gateway Amazon DynamoDB Amazon Cognito and AWS Amplify Console. Amplify Console provides continuous deployment and hosting of the static web resources including HTML CSS JavaScript and image files which are loaded in the user's browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.</p>

<h2>Application Architecture:</h2>

<img src="https://d1.awsstatic.com/diagrams/Serverless_Architecture.d930970c77b382db6e0395198aacccd8a27fefb7.png" alt="project-screenshot" width="900" height="400/">

<h2>Technologies Used:</h2>
<ul>
  <li>AWS Lambda</li>
  <li>Amazon API Gateway</li>
  <li>Amazon DynamoDB</li>
  <li>Amazon Cognito</li>
  <li>AWS Amplify Console</li>
</ul>

<br>

<h2>Getting Started:</h2>
<p>To get started with the project, follow these steps:</p>
<ul>
  <li>Set up an AWS account or use an existing one.</li>
  <li>Create a new Lambda function using your preferred programming language and runtime, and define the API Gateway routes that trigger it.</li>
  <li>Use the Amplify CLI or Console to create a new frontend web application, connect it to the API Gateway endpoint, and configure user authentication with Cognito.</li>
  <li>Use the Amplify Console to deploy the frontend assets and set up continuous deployment from your GitHub repository.</li>
  <li>Test the application by accessing the frontend URL in your browser and interacting with the API endpoints.</li>
</ul>
<br>
<p>For more information on each of the technologies used, refer to the official AWS documentation.</p>
