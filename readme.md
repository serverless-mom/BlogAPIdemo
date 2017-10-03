# demo blog api
you're welcome


## what's a sample post that the blog API might accept?

```
curl -X POST \
  http://localhost:8080/blog-posts/ \
  -H 'cache-control: no-cache' \
  -H 'content-type: application/json' \
  -H 'postman-token: b086b907-6095-9233-73c0-5256fc3dffdc' \
  -d '{"title":"Why spider-man is the smartest Avenger", "content":"youth", "author":"Toby Fee", "publishDate":9}'
```
