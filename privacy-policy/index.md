# Safari 风格新标签页隐私政策 / Privacy Policy

最后更新 / Last updated: 2026-07-06

## English

Safari Style New Tab is a Chrome new tab extension that displays bookmarks, frequently visited sites, recently closed sessions, Reading List items, and custom backgrounds locally in the user's browser.

### Data processed by the extension

The extension reads and processes the following data locally in the user's browser:

- Chrome bookmarks and bookmark folders: used to display the Favorites section on the new tab page.
- Chrome most visited sites: used to display the Frequently Visited section, including pinned sites, hidden sites, and manually added sites that should always be shown.
- Recently closed tabs and windows: used to display the Recently Closed section and to restore selected tabs or windows.
- Chrome Reading List: used to display Reading List items and to mark items as read or remove them.
- Current tab information: used to open a selected restored page in the current new tab.
- Web navigation events: used only when Chrome's native top sites data is unavailable, so the extension can maintain a local visit-count fallback.
- Site icon resources: the extension may access site-declared Apple Touch Icon, Web App Manifest icons, or favicon files to display clearer site icons.
- User settings: including section visibility, pinned and hidden site rules, manually added sites, built-in background selection, background overlay strength, custom background images, Bing wallpaper settings, focus mode state, and site icon cache. If the user selects local images or a local image folder for the background, the extension only processes files the user explicitly selects.
- Extension shortcut: the shortcut only toggles focus mode on the extension's own new tab page. The extension does not collect keyboard input.

### Data storage

All settings, site rules, local visit-count fallback data, custom background images, Bing wallpaper image data, focus mode state, and site icon cache are stored locally in Chrome storage on the user's device.

The extension does not upload bookmarks, browsing history, recently closed tabs, Reading List data, site rules, custom backgrounds, or icon cache data to any developer server.

### Data sharing

The extension does not sell, rent, transfer, or share user data. It does not use user data for advertising, profiling, or third-party analytics.

The extension does not include third-party analytics SDKs and does not execute remote code.

### Network access

The extension declares `http://*/*` and `https://*/*` host permissions to read site-declared icon URLs and download the corresponding icon resources. The same network access is also used to fetch Bing homepage wallpaper metadata and download the selected Bing wallpaper image when the user enables Bing backgrounds. The extension does not read, store, or upload page body content.

### Permission usage

- `bookmarks`: Reads and displays bookmarks and bookmark folders.
- `topSites`: Reads Chrome's native most visited sites.
- `sessions`: Reads recently closed tabs and windows and supports restoring them.
- `tabs`: Opens the selected page in the current tab and reads title, URL, and favicon information for recently closed entries.
- `readingList`: Reads and manages Chrome Reading List items.
- `storage`: Stores settings, site rules, background data, Bing wallpaper settings, focus mode state, icon cache, and local visit-count fallback data locally.
- `unlimitedStorage`: Avoids Chrome's default local storage quota when storing custom background images, Bing wallpaper image data, and high-resolution site icons locally.
- `favicon`: Uses Chrome-provided favicons as a fallback source for site icons.
- `webNavigation`: Maintains a local visit-count fallback when Chrome's native top sites data is unavailable.

### Contact

If you have questions about this privacy policy or the extension's data handling, please contact the developer through the contact information provided on the Chrome Web Store developer page.

## 中文

“Safari 风格新标签页”是一个 Chrome 新标签页扩展，用于在本地展示书签、常用网站、最近关闭、阅读列表和自定义背景。

### 数据处理范围

扩展会在用户的浏览器本地读取和处理以下数据：

- Chrome 书签和书签文件夹：用于在新标签页展示“个人收藏”。
- Chrome 最常访问网站：用于展示“最常使用”，并支持固定、隐藏和手动添加始终显示的网站。
- 最近关闭的标签页和窗口：用于展示“最近关闭”，并支持恢复。
- Chrome 阅读列表：用于展示阅读列表，并支持标记已读或移除。
- 当前标签页信息：用于在当前新标签页打开用户选择恢复的页面。
- 网页导航事件：仅在 Chrome 原生常用网站数据不可用时，用于本地统计网页打开次数。
- 网站图标资源：扩展会访问网站声明的 Apple Touch Icon、Web App Manifest 图标或 favicon，用于显示更清晰的网站图标。
- 用户设置：包括模块开关、常用网站固定和隐藏规则、手动添加的网站、背景预设、背景暗度、自定义背景图、Bing 壁纸设置、沉浸模式状态和网站图标缓存。用户也可以手动选择本机图片或图片文件夹来设置背景；扩展只会处理用户主动选择的文件。
- 扩展快捷键：用户可以通过扩展快捷键切换沉浸模式；该快捷键只用于显示或隐藏扩展自身新标签页内容，扩展不会收集键盘输入内容。

### 数据存储

所有设置、常用网站规则、访问次数统计、自定义背景图、Bing 壁纸图片数据、沉浸模式状态和网站图标缓存都保存在用户本机的 Chrome 存储中。

扩展不会把书签、浏览记录、最近关闭标签页、阅读列表、常用网站规则、自定义背景或图标缓存上传到开发者服务器。

### 数据共享

扩展不出售、不出租、不转让用户数据，也不会将用户数据用于广告、画像或第三方分析。

扩展不会嵌入第三方分析 SDK，不会执行远程代码。

### 网络访问说明

扩展声明 `http://*/*` 和 `https://*/*` 网站访问权限，用于读取网站页面中声明的图标地址并下载对应图标资源，也用于用户启用 Bing 背景时获取 Bing 首页壁纸。扩展不会读取、保存或上传网页正文内容。

### 权限用途

- `bookmarks`：读取并展示书签和书签文件夹。
- `topSites`：读取 Chrome 提供的最常访问网站。
- `sessions`：读取最近关闭的标签页和窗口，并支持恢复。
- `tabs`：在当前标签页打开用户选择的页面，并读取最近关闭记录中的标题、URL 和图标信息。
- `readingList`：读取和管理 Chrome 阅读列表。
- `storage`：本地保存设置、常用网站规则、背景图、Bing 壁纸设置、沉浸模式状态、图标缓存和访问次数统计。
- `unlimitedStorage`：避免自定义背景图、Bing 壁纸图片数据和高清网站图标触发 Chrome 默认本地存储配额。
- `favicon`：读取 Chrome 提供的网站图标作为兜底。
- `webNavigation`：在 Chrome 原生常用网站数据不可用时，本地统计网页打开次数。

### 联系方式

如果你对本隐私政策或数据处理方式有疑问，请通过 Chrome Web Store 开发者页面提供的联系方式联系开发者。
