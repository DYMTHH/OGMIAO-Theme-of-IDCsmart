# 😺 OGMIA-Theme-of-IDCsmart 😺
<img src="https://cloud.ogmiao.com/logo.webp" alt="橘喵云LOGO" width="600" />
</p>


## 🐱 项目介绍

感谢您使用OGMIAO主题！这是一个为IDCsmart魔方财务设计，它能让你的IDCsmart魔方财务界面焕然一新

---

## 📦 安装方式

```bash
# 🐾 下载主题压缩包
# 🚀 将压缩包上传至 魔方财务/public/themes/ 对应目录
# web.zip-> web
# cart.zip-> cart
# clientarea.zip-> clientarea
# 📂 解压文件，确保文件结构正确
# ✅ 在管理后台启用主题
# ‼️使用首页模板，请将魔方财务/public文件夹中404.html删除，自动使用web模板中的404定制页面
```

---

## 🏆 项目特色

📱 **全设备适配** | 从手机到电脑，各种尺寸下都能提供出色的浏览体验  
🎨 **视觉效果出众** | 精心设计的界面元素，让你的网站与众不同  

> ⚠️ **注意事项**：目前主题内容可能需要手动编辑文件进行修改，我们正在努力简化这一过程！

---

## 📋 功能清单

### 🏠 首页模板系列

- 💻 **主页面** | 清新简约的企业门户首页
- 🔧 **宝塔面板** | 快速获取宝塔合作页面
- 🤝 **合作伙伴** | 展示如何成为合作伙伴与优秀品牌联盟
- 🎯 **活动中心** | 丰富的营销活动展示
- 📜 **隐私政策** | 详细的用户隐私保护说明
- 📋 **服务条款** | 完整的服务协议与条款 
- 💡 **解决方案** | 专业的业务解决方案展示
- 🚫 **404页面** | 自定义错误页面展示

### 🛒 购物车模板

- 🎯 **瀑布流展示** | 响应式自适应布局  
- 📦 **详情展开** | 支持单击展开/收起  
- 🌍 **地区标识** | 商品地区可视化展示
- 🏷️ **分类标签** | 商品左上角支持显示标签

**📝 购物车配置说明**：

建议使用包中的cart.html作为购物车介绍内容

**设置说明：**  
> 1. 国旗展示
> - 魔方提供了各国国旗图片路径：/public/upload/common/country
> - 您可以在分类名称前（支持一，二级分类）增加：国家代号*
> - 示例：CN*香港服务器

> 2. 下方分类展开
> - 您可以在分类名称后（支持一，二级分类）增加： * yes/no（这里不应该留空白，只是因为md文件**让文字变成斜字了）
> - yes为展开，no为不展开
> - 示例：香港服务器*yes/no

**⚠️特别注意⚠️：**
> - 默认为收起不展开商品介绍状态
> - 当一级分类增加展开则下方全部二级分类商品全部展开
> - 当一级分类增加展开二级分类填no，商品状态包含被影响，您需要注意该特征⚠

> 3. 分类标签
> - 您可以在商品组标语增加：热门/无限流量/流量型/新品（只能选择一个，过多影响视觉效果所以没有多选功能）

<details>
<summary>点击展开查看配置图片（该配置显示了CN国旗并展开商品介绍还显示了热门标签）</summary>
<p align="center">
<img width="646" alt="cartpz" src="https://github.com/user-attachments/assets/6700fce6-ac64-4a8b-ada0-4ab3632c3653" />
</p>
</details>

### 👤 用户中心功能
✨ **优化设计** | 提供更好的用户体验  
我觉得用户中心有很多页面设计的不是很好，希望二开作者可以改善这个问题

**📝 用户中心配置说明**：
服务器列表显示也就是service页面，建议修改导航管理中的列表模板页

<details>
<summary>配置实例</summary>
<p align="center">
<img width="646" alt="cartpz" src="https://github.com/user-attachments/assets/5f691353-fac1-45c1-b5d9-515c4e75980b" />
</p>
</details>


💡 **定制支持**：如果您有任何特殊的页面需求，我们都可以为您定制开发！
---

### 🔍 界面预览

<details>
<summary>首页</summary>
<p align="center">
<img width="646" alt="cartpz" src="https://github.com/user-attachments/assets/7ed99537-2d50-4dce-ba9f-ae468ff11455" />
</p>
</details>

<details>
<summary>用户中心</summary>
<p align="center">
<img width="646" alt="cartpz" src="https://github.com/user-attachments/assets/8b9d64b6-d605-4c63-9258-3d8652e43751" />
</p>
</details>

<details>
<summary>购物车</summary>
<p align="center">
<img width="646" alt="cartpz" src="https://github.com/user-attachments/assets/ac13aea7-5543-408a-9ee8-8892c7ceb443" />
</p>
</details>

---

## 🌟 二开开发致谢

> 💝 我们欢迎并感谢所有二开开发的作者！每一份贡献都让这个主题变得更好！

### 🏆 优秀二开作者名录

- **@Huan-Starvm**
> 作者：Huan-Starvm
> 项目：https://github.com/Huan-Starvm/idcsmart-ogmiao-clientarea
> 主要修改了 `clientarea` 文件

- **@AnkiLove**
> 作者：AnkiLove
> 项目：https://github.com/AnkiLove/ANKI-Theme-of-IDCsmart
> 主要修改了 `web` 文件（使其看起来更粉嫩）

> 🎉 **欢迎二次开发**：我们非常支持开发者对主题进行优化和改进！如果你有新的想法：  
> - 🔄 可以自由进行二次开发  
> - 📢 建议将成果开源出来  
> - 📝 提交PR将你添加到作者名录  
> - 🤝 一起维护这个主题生态  

---

## 🌈 交流与支持

### 🎭 加入我们的欢乐社群

- 🐱 **橘喵云交流一群**：[点击加入](https://qm.qq.com/cgi-bin/qm/qr?k=-ae9KE_6u7E7tNZdjOP5dpHZenqQNWP9&jump_from=webapi&authKey=TLvq+VSp0RoeDv0JittEDYFaKKmshpy4Z89xJdL/xDhYHsofgKowdhuW5gQlvZwG)  
- 🐱 **橘喵云交流二群**：[点击加入](https://qm.qq.com/cgi-bin/qm/qr?k=Ndl5dgR-vYS3NbWUeh6r3iS1pO9rWbrx&jump_from=webapi&authKey=DgUh/PS829t9pwdJK3x9/9ZhAgfATlbuD+OT2ywq3whi/iBoPHPLlV1cG6HXvcy+)
