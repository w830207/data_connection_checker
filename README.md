### data_connection_checker

# 添加了百度ip



#### `DEFAULT_ADDRESSES`


| Address        | Provider   | Info                                              |
| :------------- | :--------- | :------------------------------------------------ |
| 1.1.1.1        | CloudFlare | <https://1.1.1.1>                                 |
| 1.0.0.1        | CloudFlare | <https://1.1.1.1>                                 |
| 8.8.8.8        | Google     | <https://developers.google.com/speed/public-dns/> |
| 8.8.4.4        | Google     | <https://developers.google.com/speed/public-dns/> |
| 180.76.76.76   | Baidu      | https://dudns.baidu.com/                          |
| 208.67.222.222 | OpenDNS    | <https://use.opendns.com/>                        |
| 208.67.220.220 | OpenDNS    | <https://use.opendns.com/>                        |

```dart
static final List<AddressCheckOptions> DEFAULT_ADDRESSES = List.unmodifiable([
  AddressCheckOptions(
    InternetAddress('1.1.1.1'),
    port: DEFAULT_PORT,
    timeout: DEFAULT_TIMEOUT,
  ),
  AddressCheckOptions(
    InternetAddress('180.76.76.76'),
    port: DEFAULT_PORT,
    timeout: DEFAULT_TIMEOUT,
  ),
  AddressCheckOptions(
    InternetAddress('208.67.222.222'),
    port: DEFAULT_PORT,
    timeout: DEFAULT_TIMEOUT,
  ),
]);
```
