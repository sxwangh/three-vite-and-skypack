###使用Skypack来处理ES Module, 无需安装，无需启动server
1、 空文件夹
2、创建index.html
```javascript
<script type="module" src="src/main.js"></script>
```
3、main.js使用SkyPack进行import package
```
import * as THREE from 'https://cdn.skypack.dev/three@0.132.2';
const scene = new THREE.Scene();
```
