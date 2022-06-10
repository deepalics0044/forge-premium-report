

This app demonstrates how to add reports in a web application from Premium Reporting APIs.

Clone or download the folder. Open the inside folder in Visual Studio Code. 

![1654835662527](C:\Users\t_srivd\AppData\Roaming\Typora\typora-user-images\1654835662527.png)

Update your client_id and client_secret in the login function of index.html



> ```javascript
>                 let clientId = "ENTER YOUR CLIENT_ID HERE" 
>                 let clientSecret="ENTER YOUR CLIENT_SECRET HERE"
>                 let scopes = "data:read+data:write+bucket:read"
>                 let redirectUri = encodeURI("http://localhost:5500")
>                 window.open(`https://developer.api.autodesk.com/authentication/v1/authorize` +
>                     `?response_type=token&client_id=${clientId}&redirect_uri=${redirectUri}&scope=${scopes}`, "_self")
>             },
> ```

Click Go live to run live server