# JWTkid_dirtraversal
this payload is for exploit the jwt token which contain kid  a.k.a key id parameter without proper escaping to retrieve the key #bitcoinCTF

usage :
ruby exploit.rb //generate payloadtoken
attack :
curl -H "Cookie: auth="[payloadtoken]" [targetURL]
