
A REST API made as a part of QSTP project that follow these criteria:  
**POST** */api/getToken*: Body of the request: The payload (can be any object). Returns the signed JWT using RS256 algorithm  
**GET** */api/secure*: The JWT returned above be sent via headers. If the token is valid, the secure data (any response will do) should be sent back else an unauthorised error.