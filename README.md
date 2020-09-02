网页版 新T树洞：[https://hole.thu.monster](https://hole.thu.monster)

## 部署

推荐使用yarn

+ 本地调试 `yarn start`
+ 打包部署 `yarn run build`


## 浏览器兼容

下表为当前 新T树洞 网页版的浏览器兼容目标：

| 平台     | Desktop |                            |         | Windows  |      | macOS  | iOS    |                     | Android |                         |
| -------- | ------- | -------------------------- | ------- | -------- | ---- | ------ | ------ | ------------------- | ------- | ----------------------- |
| 浏览器   | Chrome  | Chromium<br />(国产浏览器) | Firefox | EdgeHTML | IE   | Safari | Safari | 微信<br />(WebView) | Chrome  | Chromium<br />(WebView) |
| 优先兼容 | 76+     | 无                         | 最新版  | 无       | 无   | 无     | 12+    | 无                  | 最新版  | 无                      |
| 兼容     | 56+     | 最新版                     | 56+     | 最新版   | 无   | 10+    | 10+    | 最新版              | 56+     | 最新版                  |
| 不兼容   | 其他    | 其他                       | 其他    | 其他     | 全部 | 其他   | 其他   | 其他                | 其他    | 其他                    |


**优先兼容** 指不应有 bug 和性能问题，可以 Polyfill 的功能尽可能提供，若发现问题会立刻修复。

**兼容** 指不应有恶性 bug 和严重性能问题，若发现问题会在近期修复。

**不兼容** 指在此种浏览器上访问本网站是未定义行为，问题反馈一般会被忽略。

`num+` 指符合版本号 `num` 的最新版本及后续所有版本。`最新版` 以 stable 分支为准。

## 问题反馈

对 新T树洞 网页版的 bug 反馈请在后端仓库提交 Issue。

欢迎提出功能和 UI 建议，但可能不会被采纳。根据 AGPL，你有权自行实现你的想法。

不方便在 GitHub 上说明的问题可以邮件联系。邮件内容不会被公开。

对 新T树洞 后端服务、客户端、账号、树洞内容的反馈请联系邮件。

## License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.
    
You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
