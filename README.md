# Shopify Amp theme
The core of the project is to serve the e-commerce platform, and is committed to the rapid loading of the disease display in the user's face cleaning, so as to achieve the effect of improving the conversion rate.


# compents

1. [Google amp](https://amp.dev/zh_cn/documentation/examples/?format=websites)
2. [Shopify liquid](https://shopify.dev/api/liquid/tags/theme-tags#form)
3. [Shopify Theme kit](https://shopify.dev/themes/tools/theme-kit/getting-started)


# debug

## Theme Kit 
> Theme Kit Access 的password  [shptka_6bdffc6fcf297aae3593c8c5bec8d409]

1. 查看已存在的schema的id
```
theme get --list --password=shptka_6bdffc6fcf297aae3593c8c5bec8d409 --store="slipperhome.myshopify.com"
```
执行结果为
```
593c8c5bec8d409 --store="slipperhome.myshopify.com" 
Available theme versions:
  [133438210304][live] Dawn
  [133472911616] Shopify-AMP-Theme/master
```

2. 获取schema内容
```
theme get --password=shptka_6bdffc6fcf297aae3593c8c5bec8d409 --store="slipperhome.myshopify.com" --themeid=133472911616
```

3. Push更新到theme中
```
theme watch
```

