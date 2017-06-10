1、描述响应主体MIME类型的在Content-Type首部，描述响应主体长度的是Content-Length首部。

2、重定向

Location响应首部包含了内容的新地址或优选地址的URI
- 永久删除的资源。状态码：301 Moved Permanently
- 临时删除的资源。状态码：307 Temporary Redirect
- URL增强。意思是当请求到达时，服务器会生成一个新的包含了嵌入式状态信息的URL。状态码：303 See Other和307 Temporary Redirect
- 负载均衡。状态码：303和307
