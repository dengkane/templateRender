# templateRender

## Requirements:

1. OpenResty has been installed under /usr/local/openresty, please refer to http://www.openresty.org/ for details.


## Usage:

1. This is a simple API implemented based on lua-resty-template, and you can render templates according to rules of lua-resty-template, and the official URL is *https://github.com/bungle/lua-resty-template*.

2. The API url is *http://localhost:6699/templateRender/templateRenderApi?templateStr=select * from {{table1}}&templateValues={"table1":"t1"}* to render a template string,and please use HTTP POST method. 

3. In your applications, you can use the above URL to render templates, and recommend HTTP POST to use the APIs.



