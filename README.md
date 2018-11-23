# hash_algorithm
1. 算法
```
   public int hashCode(value) {
        int h = hash;
        if (h == 0 && value.length > 0) {
            char val[] = value;
            for (int i = 0; i < value.length; i++) {
                h = 31 * h + val[i];
            }
            hash = h;
        }
        return h;
   }
```
2. 如何计算
我们会在官网最下方表格中发布最新开奖信息，格式如下
例：
期号|区块高度|区块hash|区块时间|开奖号码
---|:--:|---:|---:|---:
A1-1001|27385896|01a1e028270a0b29f1775c6e27e9b9c9cdca003d1e4c1dcf4bcea1a57de8846a|2018-11-17T08:59:36.500|5251


