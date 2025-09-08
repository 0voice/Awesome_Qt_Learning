<h1 align="center"> Awesome Qt Learning </h1>

<p align="center">
  🌟 本仓库为一个面向开发者的 Qt 学习资源导航
</p>

<p align="center">
  💡 涵盖从基础知识到实战项目的资料与示例，帮助你快速入门、进阶和掌握 Qt 开发
</p>

> 欢迎大家 Star ⭐、Fork 🍴、贡献 PR 🙌！

---

## 📌 目录

* [简介](#-简介)
* [快速开始]()
* [学习资料]()
  * [官方文档]()
  * [入门教程]()
  * [书籍文章]()
  * [开源项目]()
  * [视频课程]()
  * [面试题]()
* [Qt 学习指南]()
  * [Qt 基础](#Qt基础)
  * [界面开发](#界面开发)
  * [核心模块](#核心模块)
  * [高级主题](#高级主题)
  * [工具与生态](#工具与生态)

---

## 📖 简介

Qt 是一个跨平台的应用程序开发框架，被广泛应用于 桌面软件、嵌入式系统、移动应用 等领域。
本仓库整理了 系统化的学习资料、示例代码、工具与社区资源，帮助开发者更高效地学习和使用 Qt。

---

## 📚 学习资料

### 官方文档

https://doc.qt.io/

### 开源项目

名称|地址|介绍
:------- | :--------------- | :------------
Clementine Music Player | [Clementine](https://github.com/clementine-player/Clementine) | 一个功能完善、跨平台的开源音乐播放器，非常适合用于学习如何开发媒体类应用，尤其是跨平台桌面应用,基于 Qt 框架开发，支持多种操作系统。
qTox | [qTox](https://github.com/qTox/qTox) | 一个功能强大、开源的即时通讯（IM）客户端，基于 Tox 协议构建。它支持端到端加密、语音和视频通话、文件传输、群组聊天等功能
TileMap地图编辑器 | [mapeditor](https://github.com/mapeditor/tiled) | 是一款非常流行的开源 2D 地图编辑器，广泛应用于游戏开发领域。
WizQTClient | [WizQTClient](https://github.com/WizTeam/WizQTClient) | 专注于提供一个优秀的个人知识管理（PKM）解决方案
DB Browser for SQLite | [DB4S](https://github.com/sqlitebrowser/sqlitebrowser) | 一个开源、跨平台的 SQLite 数据库可视化管理工具
GoldenDict | [](https://github.com/goldendict/goldendict.git) | 一款功能强大、开源的跨平台词典查询工具，支持多种本地和在线词典格式，具备优秀的排版渲染能力
QtAV | [QtAV](https://github.com/wang-bin/QtAV) | 一个基于 Qt 和 FFmpeg 的高性能跨平台多媒体播放库，旨在帮助开发者更轻松地构建功能强大的音视频播放器
JQTools | [JQ](https://github.com/188080501/JQTools) | 一个基于 Qt 框架开发的开源小工具集合，专为 Qt 开发者设计
shotcut | [shotcut](https://github.com/mltframework/shotcut) | 一款功能强大的开源视频编辑器，适用于 Windows、macOS 和 Linux 平台。
Live Helper Chat | [Live Helper Chat](https://github.com/LiveHelperChat/livehelperchat.git) | 这是一个基于 Web 的开源实时客服聊天系统。
QupZilla | [qupzilla](https://github.com/QupZilla/qupzilla) | 一个基于 Qt WebEngine（或 QtWebKit）开发的轻量级、跨平台开源网页浏览器。
Otter Browser | [otter-browser](https://github.com/OtterBrowser/otter-browser) | 一款基于 Qt WebEngine 的开源网页浏览器，旨在提供一个轻量级、可高度定制、功能齐全的现代浏览器替代方案
CuteMarkEd | [CuteMarkEd](https://github.com/cloose/CuteMarkEd) | 一个使用 Qt 框架开发的开源 Markdown 编辑器，界面简洁、功能实用，支持实时预览和多种导出格式，是学习如何构建现代 Markdown 编辑器的理想项目
Rythem | [Rythem](https://github.com/AlloyTeam/Rythem) | 一个由腾讯 AlloyTeam 开发的开源网络抓包与调试工具，可以看作是 Fiddler / Charles 的 Qt 版本实现
NitroShare | [nitroshare-desktop](https://github.com/nitroshare/nitroshare-desktop) | 一个开源的、基于局域网（LAN）的 跨平台文件传输工具，它允许你在本地网络中的设备之间快速、安全地共享和传输文件，无需依赖云服务或外部服务器
ScreenCloud | [screencloud](https://github.com/olav-st/screencloud) | 一个开源的跨平台截屏工具，支持 Windows、macOS 和 Linux 系统
Notes | [notes](https://github.com/nuttyartist/notes) | 一个使用 Qt 框架开发的开源记事本（Notepad）类桌面应用程序，界面简洁、功能实用，支持基本的文本编辑与文件管理功能
Qwt | [qwt](https://github.com/opencor/qwt) | 一个历史悠久的 Qt 扩展库，专注于提供基于 Qt Widgets 的图形绘制控件
QCustomPlot | [QCustomPlot](http://www.workslikeclockwork.com/) | 是专为 Qt 设计的轻量级、高性能绘图控件，单头文件实现，易于集成。
SerialTool | [SerialTool](https://github.com/Skiars/SerialTool) | 一个跨平台的串口/网络调试工具。此工具支持串口调试助手、终端、波形显示和文件传输等功能。

---

## Qt 基础

### Qt 简介与安装

#### Qt 是什么，能做什么

**Qt** 是一个开源的跨平台应用开发框架，由 C++ 编写而成。它不仅仅是一个 GUI（图形用户界面）库，更是一个完整的应用开发平台。它提供了丰富的 API 和工具，覆盖了从 UI 设计到网络通信、数据库、多媒体等几乎所有应用开发所需的功能。

Qt 最大的特点是 **“一次编写，处处运行”（Write Once, Run Anywhere）**。这意味着你用 Qt 编写的代码，可以轻松地编译和部署到多种操作系统上，包括 Windows、Linux、macOS、Android、iOS，甚至是各种嵌入式系统。这大大减少了跨平台开发的成本和工作量。

---

#### 安装 **Qt & Qt Creator**

你可以从 [Qt 官方网站](https://www.qt.io/)下载 **Qt 安装程序**。安装时，你需要选择不同版本的 Qt 库和编译器工具链，以及其他所需的模块。对于初学者，建议选择最新的稳定版本，并勾选一个或多个主流平台的开发套件（比如桌面版 MinGW 或 MSVC）。

[**Qt Creator**](https://www.qt.io/zh-cn/product/development-tools) 是 Qt 官方提供的集成开发环境（IDE）。它专为 Qt 开发量身定制，集成了代码编辑器、UI 设计器、调试器、项目管理等功能。它能让你轻松创建、构建、运行和调试 Qt 项目。当你安装 Qt 时，Qt Creator 通常会作为默认选项一并安装。

---

#### 项目结构（.pro / CMakeLists.txt）

Qt 项目主要有两种构建系统：**QMake** 和 **CMake**。它们都用于管理项目的编译和链接。

* **QMake**: 这是 Qt 历史悠久的构建系统，使用 **`.pro`** 文件来描述项目。它语法简单，对 Qt 特性支持良好。一个典型的 `.pro` 文件会包含源代码文件列表、头文件、模块依赖以及其他编译配置。
    * 例如：`SOURCES = main.cpp widget.cpp` 表示项目包含这两个源文件。
* **CMake**: CMake 是一个更通用的、跨平台的构建系统，使用 **`CMakeLists.txt`** 文件。CMake 功能强大，灵活性高，被越来越多的现代 C++ 项目所采用，Qt 也对它提供了很好的支持。对于大型或需要与其他 C++ 库集成的项目，CMake 往往是更好的选择。

### 核心机制

---

#### QObject 与内存管理

**`QObject`** 是 Qt 对象模型的核心类，几乎所有 Qt 类都直接或间接继承自它。`QObject` 提供了两个非常重要的功能：

1.  **父子关系（Parent-Child Relationship）**: 当一个 `QObject` 实例被创建时，你可以指定它的父对象。如果父对象被销毁，它会自动销毁所有子对象。这种机制有效地解决了内存泄漏问题，你无需手动管理每一个对象的生命周期，只需关注顶层对象的销毁即可。
2.  **信号与槽机制**: 这是 `QObject` 提供的另一个核心特性，下面会详细介绍。

---

#### 信号与槽（Signals & Slots）

**信号与槽**是 Qt 中实现对象间通信的一种高级机制，它是一种类型安全的、松耦合的事件处理方式。

* **信号 (Signals)**: 信号是一种特殊的函数，当某个事件发生时（例如用户点击了按钮），它会被“发射”出来。信号只有声明，没有实现，由 moc（元对象编译器）自动生成。
* **槽 (Slots)**: 槽是普通的 C++ 函数，用于响应信号。当一个信号被连接到一个槽上时，只要信号被发射，对应的槽函数就会被自动调用。

你可以使用 `QObject::connect()` 函数将一个对象的信号连接到另一个对象的槽。这种机制的好处是，信号的发送者和槽的接收者彼此无需知道对方的细节，从而实现了高度的解耦。

---

#### 元对象系统（QMetaObject / Q_PROPERTY）

**元对象系统**是 Qt 框架的基石，它扩展了标准 C++，提供了反射、内省（introspection）和运行时类型信息等高级功能。`QObject` 的许多核心特性，如信号与槽、动态属性等，都依赖于元对象系统。

* **`Q_OBJECT`**: 凡是需要使用信号与槽、动态属性等元对象特性的类，都必须在类声明中加上这个宏。
* **`Q_PROPERTY`**: 这个宏允许你在类中定义“动态属性”，这些属性可以像普通的成员变量一样读写，但同时具有元对象系统的特性，可以被信号槽和 QML 等访问。

---

#### 事件与事件循环（QEvent / QCoreApplication）

**事件 (QEvent)** 是用户操作、系统消息等在 Qt 应用中产生的各种“事件”。例如，鼠标点击、键盘输入、窗口大小改变等，都会被封装成一个 `QEvent` 对象。

**事件循环 (Event Loop)** 是 Qt 应用的“心脏”。它由 **`QCoreApplication::exec()`** 或 **`QApplication::exec()`** 函数启动。事件循环会不断地从事件队列中获取事件，并将其分发给相应的对象进行处理。这是一种典型的非阻塞编程模式，使得你的应用可以同时响应多种事件，而不会被某个耗时操作所阻塞。

---

## 界面开发

Qt 提供了两种主流的 UI 开发技术：**Qt Widgets** 和 **Qt Quick/QML**。它们各有优势，适用于不同的开发场景。了解它们的不同，可以帮助你选择最适合你项目的技术栈。

### Qt Widgets

**Qt Widgets** 是传统的桌面应用开发技术，它基于 C++，提供了丰富的原生风格控件。它非常适合开发经典的、功能强大的桌面应用，如 IDE、办公软件和专业工具。

* **基础控件 (QPushButton, QLabel, QLineEdit, QListView 等)**：Qt Widgets 提供了大量的现成控件，覆盖了绝大多数桌面应用需求。这些控件继承自 `QWidget`，你可以通过代码创建它们，并设置它们的属性（如文本、图标、大小等）。

* **布局管理 (QHBoxLayout, QVBoxLayout, QGridLayout 等)**：在 Qt Widgets 中，你通常不直接设置控件的绝对位置，而是使用布局管理器。布局管理器会自动调整控件的大小和位置，以适应窗口的变化。`QHBoxLayout` 用于水平排列，`QVBoxLayout` 用于垂直排列，而 `QGridLayout` 则提供了网格布局，让你能以表格形式组织控件。

* **对话框与窗口管理 (QDialog, QFileDialog, QMessageBox)**：Qt 提供了多种预设的对话框类，方便你与用户进行交互。`QDialog` 是所有对话框的基类。`QFileDialog` 用于打开或保存文件，`QMessageBox` 用于显示提示、警告或错误信息。使用这些类可以快速构建标准的交互界面。

* **自定义控件与绘图 (QPainter, QStyle, QGraphicsView)**：当标准控件无法满足需求时，你可以创建自己的自定义控件。`QPainter` 是 Qt 强大的 2D 绘图引擎，你可以用它在控件上绘制任何图形，从简单的线条和形状到复杂的图表和动画。`QGraphicsView` 框架则提供了一个强大的场景-视图架构，非常适合处理大量的 2D 图形项，例如游戏、图表编辑器等。`QStyle` 允许你更改控件的渲染风格，实现独特的外观。

---

### Qt Quick / QML

**Qt Quick** 是一种现代的、基于声明式编程的 UI 开发技术。它使用 **QML** 这种类似 JavaScript 的语言来描述 UI。Qt Quick 特别适合开发现代、流畅、动画效果丰富的应用，尤其是在移动端和嵌入式设备上。

* **QML 语法基础 (属性、信号、绑定、动画)**：QML (Qt Modeling Language) 是一种声明式语言。你通过属性（如 `width`、`height`、`color`）来定义界面元素，通过信号（如 `onClicked`）来处理用户交互。最强大的特性之一是**属性绑定**，你可以将一个元素的属性值绑定到另一个元素的属性值上，当源属性变化时，目标属性会自动更新。此外，QML 内置了丰富的动画支持，可以轻松实现平滑的过渡和动态效果。

* **Qt Quick Controls (Button, TextField, ListView 等)**：Qt Quick 提供了大量的跨平台控件，它们用 QML 编写，可以在不同设备上自动调整为原生风格。与 Qt Widgets 相比，Qt Quick Controls 更轻量，更易于定制和修改。

* **QML 与 C++ 交互 (QQmlContext, QObject 暴露给 QML)**：QML 主要负责 UI 的描述，而 C++ 则负责处理复杂的业务逻辑、数据处理和底层计算。你可以通过 **元对象系统**，将 C++ 中的 `QObject` 子类暴露给 QML。`QQmlContext` 是连接 QML 和 C++ 的关键，它允许你在 QML 中直接调用 C++ 对象的方法、访问属性，并连接信号与槽，实现了前端（QML）和后端（C++）的完美分离。

* **QML 性能优化与最佳实践**：为了确保应用的流畅性，QML 开发也需要注意性能。例如，避免在 QML 中进行复杂的计算，将耗时操作放到 C++ 后台线程中。合理使用 `Loader` 和 `Repeater` 等组件来按需加载和复用元素，从而减少内存和 CPU 开销。

---

## 高级主题

掌握了 Qt 的基础和核心模块后，就可以探索更复杂、更强大的功能了。这些高级主题能让你构建出性能更优、结构更合理、适应性更强的应用。

### 多线程编程

在任何复杂的应用中，多线程都是一个不可或缺的主题。正确使用多线程可以避免 UI 阻塞，提升应用的响应速度。

* **`QThread` / `QRunnable`**: `QThread` 是 Qt 提供的线程管理类，你可以通过继承它并重写 `run()` 方法来执行后台任务。`QRunnable` 则是一个更轻量级的接口，通常配合 `QThreadPool` 使用，用于执行一次性的、短期的任务。
* **信号槽跨线程通信**: 这是 Qt 多线程的精髓。你可以安全地在不同线程之间使用信号与槽进行通信。例如，在工作线程中发射一个信号，主线程中的槽函数会自动接收并执行，而无需担心线程同步问题。Qt 的元对象系统会自动处理线程间的同步，确保槽函数在正确的线程上下文中被调用。
* **线程池与异步任务**: `QThreadPool` 提供了一个可重用的线程集合，用于执行 `QRunnable` 任务。它避免了频繁创建和销毁线程带来的开销。`QtConcurrent` 则提供了一系列更高层次的异步函数，如 `QtConcurrent::run()`，能让你更简单地将函数放入后台线程执行，而无需直接管理线程对象。

### 插件与模块化开发

* **Qt 插件系统 (`QPluginLoader`)**: Qt 提供了一个强大的插件系统。你可以将应用的部分功能打包成独立的库文件（.dll 或 .so），然后在运行时动态加载。这让你的应用拥有可扩展性，用户可以根据需要安装或卸载功能模块。
* **动态库与模块化设计**: 插件系统的基础是动态链接库（DLL/SO）。通过将应用的不同功能划分为独立的库，可以实现更好的模块化，降低模块间的耦合，方便团队协作开发和代码重用。

### 跨平台与嵌入式

* **Windows / Linux / macOS 部署**: 掌握如何为不同的桌面操作系统打包和部署 Qt 应用是至关重要的。这包括处理依赖项、创建安装程序（例如使用 Inno Setup 或 NSIS），以及针对不同平台进行编译配置。
* **Android / iOS 移动端开发**: Qt 提供了对 Android 和 iOS 的全面支持，允许你使用 QML/C++ 编写原生风格的移动应用。你可以调用平台 API，使用传感器、摄像头等设备功能。
* **嵌入式 Qt**: Qt 是嵌入式设备上构建 UI 的热门选择，尤其是在汽车、医疗和工业控制等领域。你可以在树莓派（Raspberry Pi）等设备上运行 Qt，或者使用 Yocto 等工具构建定制化的嵌入式 Linux 系统。

### 国际化与本地化

* **翻译 (.ts 文件, Qt Linguist)**: Qt 提供了一套完整的工具链来支持多语言应用。你可以在代码中使用 `tr()` 函数标记需要翻译的字符串，然后使用 `lupdate` 工具生成 `.ts` 翻译文件。翻译人员可以使用 `Qt Linguist` 工具进行翻译，最后再用 `lrelease` 生成二进制 `.qm` 文件，供应用在运行时加载。
* **字符编码与多语言支持**: Qt 的 `QString` 类在内部使用 Unicode，这使得它能轻松处理各种语言和字符集，避免了常见的编码问题。

### 性能与调试

* **Qt Profiler**: Qt Creator 内置了一个强大的性能分析工具，可以帮助你检测应用的 CPU 使用率、内存占用和绘制性能，从而定位性能瓶颈。
* **内存与资源管理**: Qt 的父子对象模型已经为你处理了大部分内存管理，但你仍需要注意避免循环引用等问题。此外，合理使用 `QSharedPointer` 等智能指针，以及正确管理线程中的资源也是关键。
* **QML 性能优化**: 对于 QML 应用，需要特别注意性能。例如，避免在 QML 中进行复杂的 JS 计算，将数据处理放在 C++ 后台，并使用 `Loader` 和 `Repeater` 等组件来按需加载和复用 UI 元素。

---

## 工具与生态

除了强大的框架本身，Qt 还有一个完善的工具链和活跃的生态系统。这些工具能极大地提高开发效率，而丰富的第三方库则能帮助你快速扩展应用功能。

### Qt Creator IDE

Qt Creator 是专为 Qt 开发量身定制的集成开发环境。它不仅仅是一个简单的代码编辑器，更是一个集成了多种功能的强大工具。

  * **调试器**: Qt Creator 内置了强大的调试器，支持 GDB、CDB 等多种调试后端，可以方便地设置断点、查看变量、跟踪调用堆栈，帮助你快速定位和解决代码中的问题。
  * **UI 设计器 (Qt Designer)**: 对于 Qt Widgets 应用，你可以使用 **Qt Designer** 以拖拽的方式设计界面。它所见即所得，可以大大加快 UI 原型的构建速度，并自动生成可被代码调用的 UI 文件。
  * **QML 设计器**: 对于 Qt Quick 应用，Qt Creator 也提供了 QML 设计器。它让你可以在可视化的环境中编辑 QML 文件，预览 UI 效果，并进行简单的布局调整。


### 构建系统

Qt 提供了多种构建工具，以适应不同的开发习惯和项目需求。

  * **QMake**: 这是 Qt 历史悠久的构建系统，使用 `.pro` 文件。它的语法简单，与 Qt 的集成度非常高，非常适合初学者和中小型项目。
  * **CMake**: 作为现代 C++ 项目的主流构建系统，CMake 功能更强大，灵活性更高，也更容易与其他 C++ 库集成。现在，Qt 也大力推荐使用 CMake 来管理大型或复杂的项目。
    
### 常用库与扩展

Qt 的生态系统中有很多优秀的第三方库，可以为你提供额外的功能。
    
  * **Qwt (科学绘图)**: 如果你的项目涉及科学或工程领域，需要绘制复杂的曲线图、散点图等，那么 Qwt 是一个非常好的选择。它提供了强大的二维绘图组件，并与 Qt 完美集成。
    
  * **KDChart (图表)**: 这是另一个专业的图表库，提供了丰富的图表类型和高度可定制化的功能，适合需要高性能、高质量图表显示的应用。
    
  * **QScintilla (代码编辑控件)**: 如果你正在开发一个像记事本、IDE 或代码编辑器那样的应用，QScintilla 可以为你提供一个功能完善、高性能的代码编辑控件，支持语法高亮、自动补全等功能。
    
  * **Qt for Python (PySide6)**: 如果你更喜欢使用 Python 语言，那么 PySide6 提供了 Qt 的完整 Python 绑定。这使得你可以用 Python 的简洁语法来构建强大的 Qt 界面，同时仍能利用 Qt 背后强大的 C++ 性能。

---
