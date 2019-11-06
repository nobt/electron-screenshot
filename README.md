### electron非常简单的截图，轻松完成截图功能，我也是躺坑过来的
```js
const { execFile } = require('child_process');
const path = require('path');
let screenWindow = () => {
	let url = path.join(__dirname, '/win/PrScrn.exe');
	let screen_window = execFile(url);
}
module.exports = screenWindow;
```
#### 希望对你有所帮助
