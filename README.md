# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT?
Headers
PayLoad
Signature



2. What information does each part contain?
Securing an API
npm install jsonwebtoken
Node.js command
https://pruthvirajkrish.wordpress.com/2016/11/04/oauth-2-0-vs-json-web-tokens-how-to-secure-an-api/

Headers contains - 
The header declares that this thing that is being sent/recieved is a JSON Web Token and the algorithm used to generate the signature

PayLoad contains - 
Or the 'Claim' are the bulk of the info about the user that we want transferred between parties. Used to authenticate on one auth server and access protected resources another server. Used for storing a token on the app side

Signature contains - verification
Signature is generated using a private key to hash the Header and Claims.



3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/.
Because they 'compact' & 'self-contained' this helps in the process of holding claims and meta data entirely..
