# 🚀 网页上线教程（零基础版）

跟着下面的步骤做，大约 **10 分钟** 就能让网页上线，全世界都能访问。

---

## 第一步：注册 GitHub 账号

1. 打开浏览器，进入 **https://github.com**
2. 点击右上角 **Sign up**（注册）
3. 填写邮箱、密码、用户名（随便取，比如 `zhao-liang-doctor`）
4. 完成验证（拖拼图或点图片）
5. 去邮箱收验证码，输入确认
6. 选择 **Free**（免费）方案，点 Continue
7. 跳过问卷，直接点 **Skip personalization**

✅ 注册完成，你现在有了一个 GitHub 账号。

---

## 第二步：创建一个仓库（Repository）

1. 登录后，点击左上角的 **+** 号 → **New repository**
2. 填写信息：
   - **Repository name** 填：`oral-comfort`（或者你喜欢的名字）
   - **Description** 填：`口腔舒适化诊疗中心`（可选）
   - ⚠️ **一定要勾选 Public**（公开）
   - ⚠️ **不要勾选** "Add a README file"（不要勾！）
   - **不要动** 其他选项
3. 点绿色按钮 **Create repository**

✅ 仓库创建完成。页面会显示一些命令，先不用管，继续下一步。

---

## 第三步：安装 GitHub Desktop（上传文件用）

1. 下载 **GitHub Desktop**：https://desktop.github.com
2. 安装后打开，用你的 GitHub 账号登录
3. 点击 **File** → **Clone repository**
4. 选择你刚创建的 `oral-comfort` 仓库
5. 选择一个本地文件夹（比如桌面）
6. 点 **Clone**

✅ 现在你的电脑上有了一个 `oral-comfort` 文件夹。

---

## 第四步：把网页文件放进去

1. 找到刚才 Clone 下来的 `oral-comfort` 文件夹
2. 把这两个文件**复制**进去：
   - `index.html`（网页文件）
   - `qrcode.jpg`（二维码图片）
3. 回到 **GitHub Desktop**，你会看到它自动检测到了新文件
4. 在左下角的 **Summary** 框里随便写点什么，比如：`上线网页`
5. 点 **Commit to main**
6. 然后点右上角 **Push origin**

✅ 文件已经上传到 GitHub 了。

---

## 第五步：开启 GitHub Pages（让网页上线）

1. 回到 GitHub 网页（github.com），进入你的 `oral-comfort` 仓库
2. 点击 **Settings**（设置，页面上方的选项卡）
3. 左侧菜单找到 **Pages**（往下翻）
4. 在 **Source** 部分：
   - Branch 选 **main**
   - 文件夹选 **/ (root)**
   - 点 **Save**
5. 等待 1-2 分钟，页面上方会出现一个绿色提示框，显示你的网址

✅ 你的网页上线了！

网址格式是：**https://你的用户名.github.io/oral-comfort/**

---

## 🎉 完成！

现在你可以把这个网址：
- 发给患者
- 放在公众号菜单里
- 打印在名片上
- 分享到朋友圈

---

## 📱 怎么把网址放到公众号里？

### 方法一：公众号菜单跳转
1. 登录微信公众号平台（mp.weixin.qq.com）
2. 左侧菜单 → **自定义菜单**
3. 添加一个菜单项，名称比如「舒适化中心」
4. 动作选择 **跳转网页**
5. 填入你的网址：`https://你的用户名.github.io/oral-comfort/`
6. 保存并发布

### 方法二：文章里放链接
1. 写公众号文章时，在文末「阅读原文」里填入网址
2. 或者在文章正文里用文字链接引导读者访问

---

## ❓ 常见问题

**Q: 网址能改成自己的域名吗？**
A: 可以。买一个域名（比如 `oralcomfort.cn`，约 30-60 元/年），然后在 GitHub Pages 设置里绑定自定义域名。

**Q: 以后怎么更新网页内容？**
A: 修改 `index.html` 文件 → 打开 GitHub Desktop → Commit → Push。网页会自动更新。

**Q: 完全免费吗？**
A: GitHub Pages 对公开仓库完全免费，没有流量限制，没有时间限制。

**Q: 网页打开速度慢怎么办？**
A: GitHub Pages 的服务器在国外，国内访问可能稍慢。如果需要更快，可以：
- 绑定自定义域名 + 国内 CDN 加速
- 或者迁移到国内托管平台（需要域名备案）

---

## 📞 需要帮助？

如果你在任何步骤卡住了，截图发给我，我帮你解决。
