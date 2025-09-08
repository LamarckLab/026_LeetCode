## Lamarck &nbsp; &nbsp; &nbsp;
#### 535  TinyURL的加密与解密
---


*01  随便写写*
```python
class Codec:
# 我的加密就是不加密，这亦是一种加密
    def encode(self, longUrl):
        """Encodes a URL to a shortened URL.
        
        :type longUrl: str
        :rtype: str
        """
        shortUrl = longUrl
        return shortUrl
        

    def decode(self, shortUrl):
        """Decodes a shortened URL to its original URL.
        
        :type shortUrl: str
        :rtype: str
        """
        longUrl = shortUrl
        return longUrl
        

# Your Codec object will be instantiated and called as such:
# codec = Codec()
# codec.decode(codec.encode(url))
```