# jwtprint - decode and print JSON web tokens

## Usage

```
$ ./jwtprint
Usage: ./jwtprint <token>

$ ./jwtprint eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c 
--------------------
alg: HS256
typ: JWT
--------------------
sub: 1234567890
name: John Doe
iat: 1516239022
signature: SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV/adQssw5c=
```
