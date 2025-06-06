# Three.js 精简小程序版源码

本仓库提供了一个精简版的 Three.js 源码，专门适配小程序端，支持在小程序中加载3D模型、3D场景以及VR全景。该源码已在微信小程序平台进行测试，理论上支持所有支持 WebGL 的小程序平台。

## 功能特点

- **精简版源码**：针对小程序端进行了优化和精简，减少不必要的代码，提高运行效率。
- **跨平台适配**：虽然只在微信小程序平台测试过，但理论上支持所有支持 WebGL 的小程序平台。
- **示例小程序**：资源中包含使用示例小程序，方便开发者快速上手。

## 注意事项

1. **内存限制**：小程序本身占用内存有限，过于复杂的3D场景会造成运行卡顿。
2. **光影设置**：场景中的光影尽量不要太多，尤其不要开启实时阴影，会直接造成卡顿。
3. **模型大小**：加载 glb 模型时，如果模型过大，会加载时间很长。建议将模型压缩到1.5M以内。
4. **资源释放**：页面卸载时，资源不会马上释放。在页面卸载的周期函数中（例如：onUnLoad函数），务必将声明的变量修改为 null，以触发小程序的垃圾回收机制，使程序运行流畅。

## 使用方法

1. **克隆仓库**：
   ```bash
   git clone https://github.com/your-repo/threejs-mini-program.git
   ```

2. **导入小程序**：
   将源码导入到你的小程序项目中，并根据需要进行配置和调整。

3. **运行示例**：
   运行资源中的示例小程序，查看效果并参考代码实现。

## 贡献

欢迎大家贡献代码，提出问题和建议。如果你在使用过程中遇到任何问题，请在 Issues 中提出，我们会尽快回复。

## 许可证

本项目采用 [MIT 许可证](LICENSE)。

---

希望这个精简版的 Three.js 小程序源码能帮助你在小程序中实现精彩的3D效果！如果有任何问题，请随时联系我们。

## 下载链接
[Three.js精简小程序版源码](https://pan.quark.cn/s/833b292aed52) 

(备用: [备用下载](https://pan.baidu.com/s/1ebvyhZ8c_edNrz2Bf1ZgUg?pwd=1234))

## 说明

该仓库仅用于学习交流，请勿用于商业用途。
