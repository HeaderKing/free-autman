# autMan 4.8.7 (amd64)

autMan_amd64_4.8.7.tar.gz 的修改版：授权校验已绕过，解压后直接 `./autMan` 运行。

- 版本：4.8.7 (linux amd64, Go ELF)
- 运行：解压后 `chmod +x autMan && ./autMan`，HTTP 端口 8080
- 校验点：启动日志出现「授权码本地校验有效」「Http服务已运行(8080)」，`/api/system` 返回非免费版权限文案
