簡易 judge 系統怎麼做

1.  網頁題目敘述以及 function 骨架 給使用者

```go
    func somOfTwo(a int, b int){
      return
    }
```

2.  使用者 submit 答案

```go
    func somOfTwo(a int, b int){
      return a + b
    }
```

3.  service 判斷 testcase

```
    testcase1:
    input: 1, 2
    output: 3

    testcase2:
    input: 3, 5
    output: 8
```

4.  最後把 pass/fail 的結果回傳到網頁上
