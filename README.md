# Control my ceiling light

JSONをPOSTするとcountの回数だけIRKit赤外線信号送信APIを呼ぶ。

```
{
    "count":"2",
    "clientkey":"hoge",
    "deviceid":"fuga",
    "signal":{"format":"raw","freq":38,"data":[18031,8755,1190,1190,1190,3341,1190,3341,1190,3341,1190,1190,1190,3341,1190,3341,1190,3341,1190,3341,1190,3341,1190,3341,1190,1190,1190,1190,1190,1190,1190,1190,1190,3341,1190,3341,1190,1190,1190,3341,1190,1190,1190,1190,1190,1190,1190,1190,1190,1190,1190,1190,1190,1190,1190,1190,1190,3341,1190,3341,1190,3341,1190,3341,1190,3341,1190,65535,0,9379,18031,4400,1190]}
}
```
