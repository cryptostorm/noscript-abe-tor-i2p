# noscript-abe-tor-i2p
Get .onion and .i2p links working with Noscript ABE enabled. Paste the following in Noscript > Options > Advanced > ABE > System ruleset:

```
Site *.onion *.i2p 
Accept GET 
Site LOCAL 
Accept from LOCAL 
Deny
```

Cookies might still be denied by Noscript. Anyone able to help out with that issue?
