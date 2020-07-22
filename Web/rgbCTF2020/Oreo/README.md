# Oreo

## Description

This is a basic challenge which requires understanding of how cookies and encoding works.


## Sources

```
My nephew is a fussy eater and is only willing to eat chocolate oreo. Any other flavour and he throws a tantrum.
```

## Exploit

Inspecting the webpage, we find that there is a cookie named flavour, something similar to the description provided in the sources.

The cookie when decoded with base64 gives you strawberry, a flavour that the nephew doesn't prefer.

You just need to change the cookie value to chocolate encoded in base64.

Cookies always go with every request and on reload you would get the flag.

The flag is:

```
csictf{1ick_twi5t_dunk}
```
