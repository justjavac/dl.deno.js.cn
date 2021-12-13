# dl.deno.js.cn

这个网站包含了 Deno 的 release/canary 二进制安装包。Deno 主仓库 github.com/denoland/deno 的 main
分支的每次提交都会构建一个 Canary 版。

你可以通过如下的 url 下载某个 Deno 版本：

```plain
https://dl.deno.js.cn/release/v[VERSION]/deno-[TARGET_TUPLE].zip
```

你可以通过如下的 url 下载某个 Deno 的 Canary 版本：

```plain
https://dl.deno.js.cn/canary/[COMMIT_HASH]/deno-[TARGET_TUPLE].zip
```

当前 Deno 支持的平台：

- **Apple x86 (64-bit)**: x86_64-apple-darwin
- **Apple M1 (64-bit)**: aarch64-apple-darwin
- **Linux x86 (64-bit)**: x86_64-unknown-linux-gnu
- **Windows x86 (64-bit)**: x86_64-pc-windows-msvc

你还可以下载 denort (只用于 `deno compile` 的二进制 deno runtime 发行版):

```plain
https://dl.deno.js.cn/release/v[VERSION]/denort-[TARGET_TUPLE].zip
https://dl.deno.js.cn/canary/[COMMIT_HASH]/denort-[TARGET_TUPLE].zip
```

Deno 最新 release 版本 <https://dl.deno.land/release-latest.txt>。

Deno 最新 Canary 版本的 commit hash <https://dl.deno.land/canary-latest.txt>。
