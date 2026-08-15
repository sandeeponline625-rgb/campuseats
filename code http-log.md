Last login: Sat Aug 15 15:55:03 on ttys032
sandeepparmar@Sandeeps-MacBook-Air ~ % which curl
/usr/bin/curl
sandeepparmar@Sandeeps-MacBook-Air ~ % curl --version
curl 8.7.1 (x86_64-apple-darwin25.0) libcurl/8.7.1 (SecureTransport) LibreSSL/3.3.6 zlib/1.2.12 nghttp2/1.68.1
Release-Date: 2024-03-27
Protocols: dict file ftp ftps gopher gophers http https imap imaps ipfs ipns ldap ldaps mqtt pop3 pop3s rtsp smb smbs smtp smtps telnet tftp
Features: alt-svc AsynchDNS GSS-API HSTS HTTP2 HTTPS-proxy IPv6 Kerberos Largefile libz MultiSSL NTLM SPNEGO SSL threadsafe UnixSockets
sandeepparmar@Sandeeps-MacBook-Air ~ % curl -i https://jsonplaceholder.typicode.com/posts/1
HTTP/2 200 
date: Sat, 15 Aug 2026 10:43:17 GMT
content-type: application/json; charset=utf-8
content-length: 292
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"124-yiKdLzqO5gfBrJFrcdJ8Yq0LGnU"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=PD3aZ5JXmnXLLbuM9yuy2jwg6ke8U5C2Yq%2BT0erzkj0%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1775729378"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=PD3aZ5JXmnXLLbuM9yuy2jwg6ke8U5C2Yq%2BT0erzkj0%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1775729378"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 730
x-ratelimit-reset: 1775729393
age: 8280
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2b798f169ecfd02-SIN
alt-svc: h3=":443"; ma=86400

{
  "userId": 1,
  "id": 1,
  "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
  "body": "quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto"
sandeepparmar@Sandeeps-MacBook-Air ~ % curl -i https://jsonplaceholder.typicode.com/users/3

HTTP/2 200 
date: Sat, 15 Aug 2026 10:44:27 GMT
content-type: application/json; charset=utf-8
content-length: 520
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"208-uuwhfwQMzFzbJr9Pg6DKXae0SXA"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=JBBzARIeLBm8nXrdr%2Bj%2BMsge254Pms0lwCjbLfIgYOg%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1785529666"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=JBBzARIeLBm8nXrdr%2Bj%2BMsge254Pms0lwCjbLfIgYOg%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1785529666"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1785529715
age: 5314
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2b79aa90fa8c4af-SIN
alt-svc: h3=":443"; ma=86400

{
  "id": 3,
  "name": "Clementine Bauch",
  "username": "Samantha",
  "email": "Nathan@yesenia.net",
  "address": {
    "street": "Douglas Extension",
    "suite": "Suite 847",
    "city": "McKenziehaven",
    "zipcode": "59590-4157",
    "geo": {
      "lat": "-68.6102",
      "lng": "-47.0653"
    }
  },
  "phone": "1-463-123-4447",
  "website": "ramiro.info",
  "company": {
    "name": "Romaguera-Jacobson",
    "catchPhrase": "Face to face bifurcated interface",
    "bs": "e-enable strategic applications"
  }
}%                                                                                                                      sandeepparmar@Sandeeps-MacBook-Air ~ % curl -i https://jsonplaceholder.typicode.com/comments/10

HTTP/2 200 
date: Sat, 15 Aug 2026 10:45:09 GMT
content-type: application/json; charset=utf-8
content-length: 304
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"130-QdroCpYRBxteQqhUAtjOMlCo5II"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=L4QedcyBDcPmAz%2FZEyp0PlcAWySYxE1yL1oE5qA7ADg%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786727052"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=L4QedcyBDcPmAz%2FZEyp0PlcAWySYxE1yL1oE5qA7ADg%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786727052"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1786727110
age: 3623
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2b79baec9b3ab53-SIN
alt-svc: h3=":443"; ma=86400

{
  "postId": 2,
  "id": 10,
  "name": "eaque et deleniti atque tenetur ut quo ut",
  "email": "Carmen_Keeling@caroline.name",
  "body": "voluptate iusto quis nobis reprehenderit ipsum amet nulla\nquia quas dolores velit et non\naut quia necessitatibus\nnostrum quaerat nulla et accusamus nisi facilis"
}%                                                                                                                      sandeepparmar@Sandeeps-MacBook-Air ~ % curl -i https://jsonplaceholder.typicode.com/todos/5
HTTP/2 200 
date: Sat, 15 Aug 2026 10:47:27 GMT
content-type: application/json; charset=utf-8
content-length: 128
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"80-nIDrpgGIpb97HlRnMUJPolcZWGI"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=%2BFf5MdTP5kW%2FgAv3R6dqxZi5Vp1e27Vpu2pFv0m2h5M%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1785387634"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=%2BFf5MdTP5kW%2FgAv3R6dqxZi5Vp1e27Vpu2pFv0m2h5M%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1785387634"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 998
x-ratelimit-reset: 1785387636
age: 27577
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2b79f0d4886ba32-SIN
alt-svc: h3=":443"; ma=86400

{
  "userId": 1,
  "id": 5,
  "title": "laboriosam mollitia et enim quasi adipisci quia provident illum",
  "completed": false
}%                                                                                                                      sandeepparmar@Sandeeps-MacBook-Air ~ % curl -i https://jsonplaceholder.typicode.com/posts/99999
HTTP/2 404 
date: Sat, 15 Aug 2026 10:49:03 GMT
content-type: application/json; charset=utf-8
content-length: 2
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"2-vyGp6PvFo4RvsFtPoIWeCReyIC8"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=ghI7tF7I%2F76Vmc6Miw66%2BEdEvdJwMKKj7ViHaFiGYEY%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786766337"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=ghI7tF7I%2F76Vmc6Miw66%2BEdEvdJwMKKj7ViHaFiGYEY%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786766337"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1786766350
age: 24605
cf-cache-status: HIT
cf-ray: a2b7a166691a7e2e-SIN
alt-svc: h3=":443"; ma=86400
