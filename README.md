# 📘 SASS-Beamer 模板  
（适用于上海社会科学院报告与答辩）

这是一个用于学术汇报、论文答辩或讲座展示的 **Beamer 模板**，  
专为 **上海社会科学院 (SASS)** 用户定制。  
模板基于 **华东师范大学 Beamer 模板** 进行修改和优化，支持 **XeLaTeX** 编译。

---

> 💡 提示：如有自定义的 `bib` 文件或其他资源，请放入合适的子文件夹中。

---

## 🛠 编译方式

推荐使用 **XeLaTeX** 编译，以支持中文和自定义字体。

⚠️ **注意事项：**

* 请确保系统中安装了中文字体（如 `SimSun`、`SimHei`、`KaiTi`、`Noto Sans CJK` 等），否则中文可能无法正确显示；
* 模板默认基于 `XeLaTeX`，使用 `pdfLaTeX` 可能会出现字体或编码问题；
* 若包含参考文献，请按需加载 `biblatex` 或 `natbib` 宏包。

---

## 🎨 模板特色

* 🏫 **机构定制化**：模板配色、LOGO、版式均按照上海社会科学院风格设计；
* 🧱 **基于 ECNU 模板**：继承华东师范大学模板的结构与美观；
* 🈶 **全面中文支持**：内置 `xeCJK` 支持中英混排；
* 💡 **结构清晰易改**：可通过 `.sty` 文件轻松修改主题色与字体；
* 🪶 **XeLaTeX 编译友好**：无需复杂环境配置即可直接使用。

---

## 🚀 使用方法

1. 克隆或下载本仓库：

   ```bash
   git clone https://github.com/XueshuaiLiu/SASS-Beamer.git
   cd SASS-Beamer
   ```

2. 打开 `main.tex`，修改：

   * 标题（`\title{}`）
   * 作者（`\author{}`）
   * 日期与单位（`\date{}`）

3. 执行编译命令：

   ```bash
   xelatex main.tex
   ```

4. 在输出目录下获得 `main.pdf` 幻灯片文件。

---

## 📄 许可证与引用

本模板采用 [MIT License](LICENSE) 开源许可。
修改自华东师范大学 Beamer 模板，
如转载或二次开发，请保留原作者与来源说明。

---

## 📬 联系方式

如有问题、建议或改进意见，欢迎通过 [Issues 页面](https://github.com/XueshuaiLiu/SASS-Beamer/issues) 反馈，
或直接联系作者：**liuxueshuai98@gmail.com**

---

感谢使用本模板，祝你的报告与答辩顺利！
