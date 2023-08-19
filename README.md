# JWT-Backend
How JWT works on the backend with refreshing tokens and node.js

#REQUESTS:
GET http://localhost:3000/posts
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoiS3lsZSIsImlhdCI6MTY5MjQzMDk3NSwiZXhwIjoxNjkyNDMyNDc1fQ.ZQu4LGlB2dV5XQIlOd5_FsbtE2BYTeOKMnkdNi4Jp3U
###

POST http://localhost:4000/token
Content-Type: application/json

{
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoiS3lsZSIsImlhdCI6MTY5MjQzMDk3NX0.XLmwg_Gc7s2yOg4Sl51RSNfUERDKvHGWVBH9YWlWYfQ"
} 

###
POST http://localhost:4000/login
Content-Type: application/json

{
    "username": "Kyle"
}
