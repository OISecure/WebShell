# WebShell 
# This is a PHP code snippet that can execute system commands via a web request.
# This is a dangerous piece of PHP code that could potentially allow an attacker to execute arbitrary shell commands on the server where the code is running.
# The code uses the system function to execute the command passed as a parameter to the command variable in the $_REQUEST superglobal array.
# The input is first decoded from base64 encoding using the base64_decode function. 
# This code should never be used on a public-facing server, as it poses a serious security risk.
