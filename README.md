How to install

```

pip3 install pycrybittrex

```

or with conda

```

conda install -c namiazad pycrybittrex

```

Usage example:

```python

from pycrybittrex import bittrex, ApiVersion
client = bittrex.create_client(ApiVersion.V1_1, api_key='<api_key>', api_secret='<api_secret>')
order_history = client.get_order_history("ETH-XRP")

```







