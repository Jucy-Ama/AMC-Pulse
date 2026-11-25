# AMC Pulse

一键给店铺的人群包把个脉：在 Tableau「AMC for SpAds Performance」看板上，一键抓取 Salesforce 账户 → 自动取店铺 / 类目 AMC 数据 → 生成人群包交叉分析看板、Excel 与卖家话术。

## 安装（Chrome / Edge / Firefox）
1. 安装浏览器扩展 **Tampermonkey**
2. Chrome / Edge：打开 `chrome://extensions`（或 `edge://extensions`）开启「开发人员模式」；新版 Chrome 还需在 Tampermonkey「详细信息」里打开「允许用户脚本」
3. 点击安装：**[AMC_Pulse.user.js](https://raw.githubusercontent.com/Jucy-Ama/AMC-Pulse/main/AMC_Pulse.user.js)** → 在弹出的油猴页面点「安装」

之后有新版本会自动更新。

## 使用
1. 在浏览器中登录 Tableau Cloud 和 Salesforce
2. 打开 AMC for SpAds Performance 看板，点击右下角圣诞老人
3. ① 抓取账户 → ② 选择账户 → ③ 时间范围 → 下载并生成
4. 在弹出的看板中选择语言 / 高亮，复制卖家话术，下载 Excel 或导出 HTML
