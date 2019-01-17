 [Suggested description]
 The vulnerability is located in the user name of the background management login page. The user name has a sql injection vulnerability here, which can bypass the login by using the universal password and unauthorized access to the background page.
 
 [Vulnerability Type]
 Unauthorized access
 sql inject
 
 [Vendor of Product]
 http://www.mogooo.com/
 
 [Affected Product Code Base]
 mogoooo enterprise manage platform v1
 
  [Affected Component]
  affected page is /admin/login.aspx
  affected parameter is tb_loginuser
  
  [Attack Type]
  remote
  
  [Attack Vectors]
  when you login,you can input the payload 'or'='or' in username and password. then,you will login in the manage page.
  
