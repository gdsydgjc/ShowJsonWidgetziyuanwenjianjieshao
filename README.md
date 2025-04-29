# ShowJsonWidget 资源文件介绍

## 概述

`ShowJsonWidget.zip` 是一个由 QT 编写的控件资源文件，主要包含一个带有行号的 `QTextEdit` 控件。该控件适用于需要展示 JSON 数据或其他文本内容的场景，提供了清晰的行号显示，便于用户快速定位和查看文本内容。

## 功能特点

- **行号显示**：在 `QTextEdit` 控件的左侧显示行号，方便用户快速定位文本内容。
- **JSON 格式化**：支持 JSON 数据的格式化显示，使数据结构更加清晰易读。
- **自定义样式*8：可以通过设置样式表（QSS）来调整控件的外观，满足不同项目的需求。

## 使用方法

1. **下载资源文件**：
   - 从本仓库下载 `ShowJsonWidget.zip` 文件。

   2. **解压文件**：
      - 解压 `ShowJsonWidget.zip` 文件，获取其中的源代码和资源文件。

      3. **集成到项目**：
         - 将解压后的文件集成到你的 QT 项目中。
            - 在需要使用该控件的界面文件中，引入相关头文件并实例化 `ShowJsonWidget` 控件。

            4. **自定义设置**：
               - 根据项目需求，通过设置样式表或其他属性来调整控件的外观和行为。

               ## 示例代码

               以下是一个简单的示例代码，展示如何在 QT 项目中使用 `ShowJsonWidget` 控件：

               ```cpp
               #include "ShowJsonWidget.h"
               #include <QApplication>

               int main(int argc, char *argv[])
               {
                   QApplication app(argc, argv);

                       ShowJsonWidget widget;
                           widget.setJsonText("{\"key\":\"value\"}");
                               widget.show();

                                   return app.exec();
                                   }
                                   ```

                                   ## 贡献与反馈

                                   如果你在使用过程中遇到任何问题，或者有改进建议，欢迎提交 Issue 或 Pull Request。我们非常欢迎社区的贡献，共同完善这个控件。

                                   ## 许可证

                                   本项目采用开源许可证，具体许可证信息请参阅项目根目录下的 `LICENSE` 文件。

                                   ---

                                   希望 `ShowJsonWidget` 能够帮助你在 QT 项目中更方便地展示和编辑 JSON 数据！

                                   ## 下载链接
                                   [ShowJsonWidget资源文件介绍](https://pan.quark.cn/s/e8f694cb7d11) 

                                   (备用: [备用下载](https://pan.baidu.com/s/1iEmlOkkufByEcvtjiAex7Q?pwd=1234))

                                   ## 说明

                                   该仓库仅用于学习交流，请勿用于商业用途。
