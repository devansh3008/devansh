# SubdomainEnum

SubdomainEnum is tool which is used for discovering subdomains using custom wordlist file.
## Subdomain

A subdomain is a domain that is part of a larger domain; the only domain that is not also a subdomain is the root domain. For example, west.example.com and east.example.com are subdomains of the example.com domain, which in turn is a subdomain of the com top-level domain (TLD).

![subdomain](https://user-images.githubusercontent.com/30910269/82931733-fdd0e480-9fa4-11ea-91c3-f51c1f6e75b4.png)

### Requriments:
1) requests
2) optparse

#### Download Requirments:

pip install -r requirements.txt

##### Tool Usage:

![carbon-2](https://user-images.githubusercontent.com/30910269/82932344-eba37600-9fa5-11ea-891c-18ccacfee94e.png)

###### Download:
1) git clone https://github.com/devansh3008/SubdomainEnum.git
2) cd SubdomainEnum
3) python SundomainEnum.py -d domain -w wordlist
