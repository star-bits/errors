# Common error messages

URLError: <urlopen error [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1123)>
```
import ssl

ssl._create_default_https_context = ssl._create_unverified_context
```
