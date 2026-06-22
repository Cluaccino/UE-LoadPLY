# 📦 UE-LoadPLY

**UE-LoadPLY** 是一个为 **Unreal Engine 5.6** 设计的轻量级插件，用于加载 **PLY（Polygon File Format）** 点云与高斯 3D 资产文件。

---

## ✨ 特性

- 🚀 **开箱即用** — 复制文件夹、重启引擎，即可开始使用
- 🧩 **原生 C++ 实现** — 高性能解析，无缝集成 UE 资产系统
- 🎯 **专为 UE 5.6 优化** — 适配最新引擎 API
- 📁 **支持点云 / 高斯 3D 数据** — 适用于 3D 扫描、场景重建等场景

---

## 📥 安装

### 1️⃣ 克隆仓库

```bash
git clone https://github.com/Cluaccino/LoadPLY.git
```

### 2️⃣ 切换分支

```bash
git checkout UE5.6
```

> 📌 **注意**  
> `main` 分支为稳定主线，`UE5.6` 分支为当前插件对应版本。

### 3️⃣ 复制到项目

将 `Plugins/loadplyPlugin` 文件夹复制到你的 UE 项目根目录下的 `Plugins/` 文件夹中。

```
YourProject/
├── Plugins/
│   └── loadplyPlugin/   ← 复制到这里
├── Content/
└── ...
```

### 4️⃣ 重启引擎并启用插件

重启 Unreal Engine，编辑器会自动编译插件。随后在 **项目设置 → 插件** 中启用 `loadplyPlugin`。

---

## 🎮 使用

启用插件后，你可以通过以下方式使用 PLY 加载功能：

- **蓝图** — 使用插件提供的蓝图节点加载 PLY 资产
- **运行示例地图** — 打开插件自带的 `loadplyPlugin/Content/Blueprints/NewMap` 地图并运行，即可看到 PLY 加载演示

> 💡 详细 API 文档请参考插件源码中的注释。

---

## 📚 相关链接

- [GitHub 仓库](https://github.com/Cluaccino/UE-LoadPLY)
- [Unreal Engine 官方文档](https://docs.unrealengine.com/)

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/Cluaccino">Cluaccino</a>
</p>

---

# 📦 UE-LoadPLY

**UE-LoadPLY** is a lightweight plugin for **Unreal Engine 5.6** that enables loading **PLY (Polygon File Format)** point cloud and Gaussian 3D assets.

---

## ✨ Features

- 🚀 **Plug & Play** — Copy the folder, restart the engine, and you're ready to go
- 🧩 **Native C++ Implementation** — High-performance parsing with seamless UE asset integration
- 🎯 **Optimized for UE 5.6** — Compatible with the latest engine APIs
- 📁 **Supports Point Cloud & Gaussian 3D Data** — Ideal for 3D scanning, scene reconstruction, and more

---

## 📥 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Cluaccino/LoadPLY.git
```

### 2️⃣ Switch to the Correct Branch

```bash
git checkout UE5.6
```

> 📌 **Note**  
> The `main` branch is the stable trunk, while `UE5.6` is the version corresponding to the current plugin.

### 3️⃣ Copy to Your Project

Copy the `Plugins/loadplyPlugin` folder to the `Plugins/` directory under your UE project root.

```
YourProject/
├── Plugins/
│   └── loadplyPlugin/   ← Copy here
├── Content/
└── ...
```

### 4️⃣ Restart & Enable

Restart Unreal Engine — the editor will automatically compile the plugin. Then enable `loadplyPlugin` in **Project Settings → Plugins**.

---

## 🎮 Usage

After enabling the plugin, you can load PLY assets via:

- **Blueprints** — Use the provided Blueprint nodes
- **Run the example map** — Open the built-in map `loadplyPlugin/Content/Blueprints/NewMap` and play it to see a PLY loading demo

> 💡 For detailed API documentation, refer to the comments in the plugin source code.

---

## 📚 Links

- [GitHub Repository](https://github.com/Cluaccino/UE-LoadPLY)
- [Unreal Engine Documentation](https://docs.unrealengine.com/)

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/Cluaccino">Cluaccino</a>
</p>
