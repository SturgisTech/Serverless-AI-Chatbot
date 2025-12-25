**AWS 🚀 Serverless AI Chatbot with Amazon Bedrock, Lambda, API Gateway & S3 🤖**
<img width="1280" height="562" alt="chatbot diagram" src="https://github.com/user-attachments/assets/b2f9be86-f498-4fd3-849f-7cef6b6ef9dd" />

🔎 **Overview**

      -Users interact with the chatbot through a static frontend (S3 / Amplify) or by calling the API directly.
      -Requests are sent via API Gateway to AWS Lambda, which uses an IAM role to securely invoke 
         Amazon Bedrock (Titan Text G1 – Express).
      -Responses are returned back through the same path to the user.

      ⚡ Fully serverless, scalable, and secure.

🛠 **Tech Stack**

      🤖 Amazon Bedrock (Titan Text G1 – Express)

      ⚡ AWS Lambda

      🌐 Amazon API Gateway

      🗂️ Amazon S3 (Static Hosting)

      💻 JavaScript, HTML, CSS
