# Orange-Penguen-Library
## Description
This is a password generator that is created with a hash code philosophy. Inside the library, the hash_generator() takes 2 arguments. The first one is the password you want to hash and the other one is the key for more security. Key can be simple numbers or short texts. This library is in development. If you manage to write any decoder or find anything nonsense to you feel free to send an email to me.


[PyPi Link](https://pypi.org/project/orngpenguen/0.0.1/)

[Colab Sample Code Link](https://colab.research.google.com/drive/1jp1WzqbyfbCaPbfvQ5audFYaaclXD_nr#scrollTo=umhSxjZlAG_r)


## Usage
```python
import orngpenguen

#Getting password and key from the user
passwd, key = orngpenguen.Penguen.input_hash()  

#Choose password length (Default character length is 15)
passwd_len = 35

#Run Hash Algorithm
hash = orngpenguen.Penguen.hash_generator(passwd,key,passwd_len)
print("Hash password: ", hash)

```


