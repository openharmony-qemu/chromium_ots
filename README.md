# chromium_ots

OpenType Sanitizer (OTS)：一个字体文件“消毒”库。它解析并清理 Web 字体（TTF, WOFF2 等），以防止恶意字体文件利用渲染引擎的漏洞。
核心安全组件。在渲染任何 Web 字体之前，Chromium 必须使用 OTS 对其进行处理，以防范 RCE（远程代码执行）攻击。
