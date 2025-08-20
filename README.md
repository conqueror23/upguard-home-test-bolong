# upguard-home-test

This Repo is for upguard take home test

The main platform used to develop this project is n8n.io

Domain : https://bolongwang.app.n8n.cloud

## prerequsite

1. OpenAI API key
2. Google Client key & secret
3. Company Enrich service API key
4. Pinecone API key

## Dependencies 

1. [OpenAI](https://platform.openai.com/) 
2. [Google Cloud Console](https://console.cloud.google.com/welcome?hl=en&inv=1&invt=Ab5_TA&project=n8n-playground-469414)
3. [Company Enrich service](https://app.companyenrich.com/)
4. [pinecone vector database](https://app.pinecone.io/)

## Files structure explanations

root
|
 +input: input of workflow
 |_Sales Preparation Report Template.pdf  -- processed by embedding model and stores into pinecone vector database 
| 
|_output: output of workflow
   
