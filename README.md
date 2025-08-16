# ClashMeta-Script
A website to transfer proxy Link to Clash.Meta profile
---

### **节点链接转 Clash.Meta 配置工具**

这是一个轻量级的、完全在浏览器中运行的在线工具，旨在帮助您快速、安全地将各种常见的代理节点链接转换为 Clash.Meta 客户端兼容的 YAML 配置文件。

#### ✨ **核心功能**

*   **广泛的协议支持**: 支持 VLESS、Trojan、Shadowsocks (SS)、VMess、Hysteria/2、TUIC、WireGuard 等当前主流及前沿的代理协议。
*   **智能命名**: 自动识别 VLESS 和 Trojan 协议的加密方式，并在节点名称中明确标注 `TLS` 或 `REALITY`，使配置一目了然。
*   **客户端处理，保障隐私**: 所有转换操作均在您的浏览器本地完成，节点链接等敏感信息**不会**被发送到任何服务器，确保您的隐私安全。
*   **灵活的输出选项**:
    *   **完整配置**: 一键生成包含代理节点、代理组和基础分流规则的 `config.yaml` 文件，可直接导入 Clash.Meta 使用。
    *   **仅代理列表**: 只生成 `proxies:` 部分，方便您手动将其追加到现有的配置文件中。
*   **简单易用**: 只需将节点链接粘贴到输入框，点击“生成”即可。同时提供“复制”和“下载”按钮，方便您使用结果。

#### 🚀 **如何使用**

1.  将您的节点链接（每行一个）粘贴到文本输入框中。
2.  根据需要，勾选或取消“生成完整配置”。
3.  点击 **“生成”** 按钮。
4.  生成的配置会显示在下方的代码框中。
5.  点击 **“复制”** 将配置内容复制到剪贴板，或点击 **“下载”** 将其保存为 `.yaml` 文件。

#### ✅ **支持的协议列表**

*   **VLESS** (支持 TLS 和 REALITY)
*   **Trojan** (支持 TLS 和 REALITY)
*   **Shadowsocks (SS)** (兼容 SS2022 和 v2ray-plugin)
*   **VMess**
*   **Hysteria**
*   **Hysteria2**
*   **TUIC v5**
*   **WireGuard**
*   **SOCKS5**
*   **HTTP/HTTPS Proxy**

---

### English Version

---

### **Proxy Link to Clash.Meta Converter**

This is a lightweight, browser-based online tool designed to help you quickly and securely convert various common proxy node links into a YAML configuration file compatible with the Clash.Meta client.

#### ✨ **Core Features**

*   **Broad Protocol Support**: Supports a wide range of current and next-generation proxy protocols, including VLESS, Trojan, Shadowsocks (SS), VMess, Hysteria/2, TUIC, WireGuard, and more.
*   **Intelligent Naming**: Automatically detects the encryption mode for VLESS and Trojan protocols, and explicitly labels nodes with `_TLS` or `_REALITY` in their names for enhanced clarity.
*   **Client-Side Processing for Privacy**: All conversion logic runs locally in your browser. Sensitive information like your node links will **never** be sent to any server, ensuring your privacy is protected.
*   **Flexible Output Options**:
    *   **Full Configuration**: Generate a complete `config.yaml` file with one click, including proxies, proxy groups, and basic routing rules, ready for direct import into Clash.Meta.
    *   **Proxies Only**: Generate only the `proxies:` list, making it easy to manually append to your existing configuration file.
*   **Easy to Use**: Simply paste your node links into the input area and click "Generate". Convenient "Copy" and "Download" buttons are provided for easy access to the output.

#### 🚀 **How to Use**

1.  Paste your node links (one per line) into the text input area.
2.  Check or uncheck the "Generate full config" option as needed.
3.  Click the **"Generate"** button.
4.  The generated configuration will appear in the code block below.
5.  Click **"Copy"** to copy the configuration to your clipboard, or **"Download"** to save it as a `.yaml` file.

#### ✅ **Supported Protocols**

*   **VLESS** (with TLS and REALITY support)
*   **Trojan** (with TLS and REALITY support)
*   **Shadowsocks (SS)** (compatible with SS2022 and v2ray-plugin)
*   **VMess**
*   **Hysteria**
*   **Hysteria2**
*   **TUIC v5**
*   **WireGuard**
*   **SOCKS5**
*   **HTTP/HTTPS Proxy**
