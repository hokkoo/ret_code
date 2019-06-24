# ret_code

## 项目使用及说明

### 安装
`npm i ret_code`

### 使用
```
import retcode from 'ret_code';
ctx.body = {
    ret : retcode.ok,
};
```

ret   | key     | mean
--    | --      | --
0     | ok      | 成功
99999 | fail    | 操作失败
50000 | err     | 系统错误
40000 | noallow | 没有权限

- `按照项目，可以自行扩展其他的返回码`
- 团队讨论后可以补充通用返回码到这里
