## OBJECTIVE
- To intercept and analyze login authentication traffic using Burp Suite
  in order to understand how credentials are transmitted between client and server

  ## Tools Used
  - Burp Suite Community Edition
  - OWASP Juice Shop (local instance)
  - Web browser (The one embedded in Burp)
 
  ## Procedure
  - Started OWASP Juice Shop locally on: http//localhost:3000
  - Opened Burp Suite and enabled: Proxy --> Intercept ON
  - Launched Burp browser and navigated to: http://localhost:3000
  - Attempted login with some credentials
  - Captured the request: POST/rest/user/login

  ## Captured Request (Analysis)
  - Method: POST
  - Endpoint: /rest/user/login
  - Request Body:
    {
     "email": "formejoogybr@gmail.com",
     "password": "fucksakesjhuhu"
    }

    ## Observations
    - Credentials are sent in JSON format
    - Request uses HTTP POST method
    - Data is transmitted to a Rest API endpoint
    - This endpoint is potential target for
        >> SQL Injection
        >> Authentication bypass
        >> Brute-force attacks

  ## Security insight
  Login endpoints are critical attack surfaces because:
  - They handle sensitive data (Credentials)
  - Poor validation can lead to unauthorized access
  - They are often targeted in real-word attacks
 
  ## Conclusion
  This exercis demonstrates how attackers and security analysts can:
  - intercept login requests
  - inspect transmitted data
  - identify potential vulnerabilities in authentication systems
    
