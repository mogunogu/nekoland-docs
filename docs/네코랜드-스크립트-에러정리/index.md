# 네코랜드 스크립트 에러 정리


## attempt to index ~ 에러


### `attempt to index nil value` 에러


#### 에러가 나는 상황 예시

```lua
a = f
b = a[1] -- attemp to index nil value
```

```lua
print(a) -- nil
c = a.atk * 2 -- attemp to index nil value
```


