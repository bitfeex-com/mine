# 挖矿算法

[线性随机](https://github.com/fl00r/pickup)

```ruby
p = Pickup.new(miners_hash["miners"], key_func: ->(item){ item["uid"]}, weight_func: ->(item){ item["target"]})
coinbase = p.pick
```
