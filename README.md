# sociallogin
social login spring security + boot + google and github oauth2
<br/>



# Steps to create developer account in google and github-<br/>
1.Goto google developer console and create your own clientId and client-secret.<br/>.
2.Import maven project.<br/>
3.Replace "security.oauth2.client.clientId" with your generated id in "application.properties".<br/>
4.Replace "security.oauth2.client.clientSecret" with your client-secret.<br/>
5.Run "Oauth2Application" as main application.<br/>
6."http://localhost:8081" url in any browser to test.<br/>
 
Similarly goto github. login-> settings->OAuth tabs-> create application <br/>
After that add any application name.<br/>
homepage url : http://localhost:8081<br/>
Authorization callback URL: http://localhost:8081/login/oauth2/code/github<br/>
then copy client-id and client-secret.
