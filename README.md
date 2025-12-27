### 📋 场景一：开始干活（项目启动）

#### 1. 把 GitHub 上的仓库搬到本地
*   **场景**：你要开始做 `my-ai-agent-toolkit` 项目了。
*   **操作**：
    ```bash
    cd ~/Desktop                  # 1. 先去桌面（或其他目录）
    git clone https://...git      # 2. 从云端克隆下来
    code my-ai-agent-toolkit      # 3. 直接用 VS Code 打开它
    ```

#### 2. 从零新建一个新项目
*   **场景**：灵光一闪，想做一个新的 `sales_agent`。
*   **操作**：
    ```bash
    cd ~/Desktop                  # 1. 去桌面
    mkdir my-new-ai-agent         # 2. 新建空文件夹 (Make Directory)
    code my-new-ai-agent          # 3. 直接用 VS Code 打开它
    ```

---

### 🚀 场景二：像极客一样打开 VS Code

#### 1. “就在这里打开” (最常用)
*   **场景**：你已经在终端里进入了某个文件夹，想呼唤 VS Code。
*   **指令**：
    ```bash
    code .
    ```
    *(注意：`code` 后面有个**空格**，然后是**点**。点代表“当前目录”。)*

#### 2. “打开指定位置”
*   **场景**：你刚打开终端，懒得 cd 进去。
*   **指令**：
    ```bash
    code ~/Desktop/my-ai-agent-toolkit
    ```

---

### 💾 场景三：Git 存档三部曲 (网购模型)

**前提**：记得先按 `Cmd + S` 保存文件！

#### 1. 放入购物车 (Add)
*   **作用**：告诉 Git 哪些文件变了。
    ```bash
    git add .
    ```
    *(注意：点代表“所有文件”)*

#### 2. 下单结算 (Commit)
*   **作用**：生成永久的历史存档（后悔药）。
    ```bash
    git commit -m "这里写你干了什么"
    ```

#### 3. 快递发货 (Push)
*   **作用**：同步到 GitHub 云端。
    ```bash
    git push
    ```

---

### ⚡️ 场景四：VS Code 里的神级快捷键

#### 1. 切换项目 (Switch Project)
*   **场景**：从 `toolkit` 项目切换到 `learning` 项目，不用关窗口。
*   **按键**：**`Control + R`**
    *   *(注意：是 Control ⌃，不是 Command ⌘)*

#### 2. 呼唤上帝 (Command Palette)
*   **场景**：你要找任何功能（比如 `Git Clone`，`Auto Save`），但找不到菜单在哪。
*   **按键**：**`Command + Shift + P`**
    *   *这是 VS Code 的万能入口。*

#### 3. 呼唤 Mac 搜索
*   **场景**：你要找文件夹、找软件。
*   **按键**：**`Command + 空格`**

---