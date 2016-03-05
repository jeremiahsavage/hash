# hash

##MD2

```bash
$ gcc *.c -D'MD=2' -o md2
```

```bash
$ ./md2 -t
MD2 time trial. Digesting 1000 1000-byte blocks ... done
Digest = cab5af27d5da78a05da6f6fb1e6293cf
Time = 1 seconds
Speed = 1000000 bytes/second
```

```bash
$ ./md2 -x
MD2 test suite:
MD2 ("") = 8350e5a3e24c153df2275c9f80692773
MD2 ("a") = 32ec01ec4a6dac72c0ab96fb34c0b5d1
MD2 ("abc") = da853b0d3f88d99b30283a69e6ded6bb
MD2 ("message digest") = ab4f496bfb2a530b219ff33031fe06b0
MD2 ("abcdefghijklmnopqrstuvwxyz") = 4e8ddff3650292ab5a4108c3aa47940b
MD2 ("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789") = da33def2a42df13975352846c30338cd
MD2 ("12345678901234567890123456789012345678901234567890123456789012345678901234567890") = d5976f79d83d3a0dc9806c3c66f3efd8
```
