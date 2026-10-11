# 雨中冒险 (Rainy Platform Adventure)

一个纯前端、零依赖的单文件平台跳跃小游戏：跳过障碍、踩上平台、寻找避雨棚，穿越雨幕抵达最右侧的出口，挑战无限关卡。

## 在线试玩

不用下载、不用安装，点开链接就能玩：

**https://han1235101.github.io/rain-escape/**

## 玩法

1. 点击「开始冒险」
2. 用 `←` `→` 或 `A` / `D` 左右移动
3. 用 `空格` / `↑` / `W` 跳跃
4. 站在雨棚下方的平台上即可避雨；碰到障碍不会死亡，被雨淋到才会失败
5. 抵达最右侧的出口即通关，得分并进入下一关

## 本地运行

没有构建步骤，也没有第三方依赖。直接用浏览器打开 `index.html` 即可。

如果你想通过本地服务运行：

```bash
python3 -m http.server 8000
# 然后访问 http://localhost:8000/index.html
```

## 部署到 GitHub Pages

本仓库的 `main` 分支根目录已开启 GitHub Pages。页面是纯静态的，任何改动推送到 `main` 后会自动更新，无需额外构建。

## 技术

- HTML + CSS
- Canvas 2D 绘制
- 原生 JavaScript（无框架）

## 许可

本项目基于 [MIT License](LICENSE) 开源。
