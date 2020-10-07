# VuePress Multi Nested Tab

::::::: tabs

:::::: tab Mainnet

::::: tabs

:::: tab Python

```python
import bit
key = bit.Key.from_bytes(b'REPLACE_WITH_YOUR_RANDOM_STRING')
print(key.segwit_address)
```
::: tip Tip: create a random key

You can print a criptographically safe private key in python like this:

```python
import os
import bit
random_bytes = os.urandom(16)
private_key_WIF = bit.key.from_bytes(random_bytes).to_wif()
print(private_key_WIF)
```

:::

::::

:::: tab Javascript

```javascript
console.log("Hello world");
```

::::

:::::

::::::

:::::: tab Testnet

Other tabs and contents will goes here

::::::

:::::::
