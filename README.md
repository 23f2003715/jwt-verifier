# JWT Verification API

POST /verify

Body

{
  "token":"<jwt>"
}

Success

{
  "valid": true,
  "email":"...",
  "sub":"...",
  "aud":"..."
}

Failure

{
  "valid": false
}
