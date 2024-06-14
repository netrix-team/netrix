# Netrix
Package for interacting with Netrix API

## Installing
```
pip install netrix
```
## Example
```py
from netrix import Netrix

API_KEY = 'e5495e14-a60f-4804-b4f6-f1a1938ae984'
net = Netrix(api_key=API_KEY)

def main():
    user_id = '461219084802195477'
    info = net.get_user_info(user_id)
    return info

if __name__ == '__main__':
    main()
```
