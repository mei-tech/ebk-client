# ebk-client - an eBay Kleinanzeigen API client
ebk-client is a small library to use the eBay Kleinanzeigen/Classifieds API.  

## Usage
Besides the normal user account which can be registered at [ebay-kleinanzeigen.de](https://www.ebay-kleinanzeigen.de), a special partner eBay partner account is required to use the eBay Kleinanzeigen/Classifieds API.  
The smartphone apps (e.g. for Android) must include also some static/hardcoded partner account as it is using the same API

### Code example:
```python
api = EbkClient('app-username', 'app-password', 'ebay-user-name', 'ebay-user-password')
my_ads = api.get_my_ads()
```

## Documentation
No ebk-client doc available yet.  
The official documentation of the eBay Kleinanzeigen/Classifieds API is described [here](https://api.ebay-kleinanzeigen.de/docs/pages/home)

## Requirements
 * Python 2
 * dateutil (example.py only)
