Download the code if not , download the .rar and extract open this file in Eclipse

Download the ADVANCED REST client to test API

INSTRUCTIONS:

1.Clear port 8080 then,run the SpringBootHelloWorldApplication in debug mode.

2.Go to url: http://localhost:8080/authenticate in method: POST on the "ADVANCED REST client" and enter in the body a json array : {"username":"javainuse","password":"password"}.

3.Copy the token generated.

4.Go to url: http://localhost:8080/hello in method: GET on the "ADVANCED REST client" and create a new header and name it as Authorization in the value type: Bearer <paste copied token>

5.Thank you.
