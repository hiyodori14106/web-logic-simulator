# Web Logic Simulator ⚡

A high-performance, browser-based digital logic circuit simulator built with vanilla JavaScript and HTML5 Canvas.  
バニラJavaScriptとHTML5 Canvasで作られた、高性能なブラウザベースのデジタル論理回路シミュレータです。

🔗 **[Live  / 試す](https://hiyodori14106.github.io/web-logic-simulator/)**  
*(↑ After enabling GitHub Pages, replace YOUR_USERNAME with your GitHub ID / GitHub Pages有効化後、自分のIDに書き換えてください)*

---

## ✨ Features / 特徴

*   **🚀 High Performance**: Optimized rendering using HTML5 Canvas (Smooth 60fps+).  
    HTML5 Canvasを使用した最適化されたレンダリング（60fps以上で滑らかに動作）。
*   **🧩 Custom IC Creation**: Group selected components and convert them into your own reusable Integrated Circuits.  
    選択した部品をグループ化し、独自のICチップとして再利用可能にする機能。
*   **🌐 Multi-Language Support**: English, Japanese, Chinese (Simplified), Spanish, Portuguese, and Korean.  
    多言語対応（英語、日本語、中国語、スペイン語、ポルトガル語、韓国語）。
*   **💾 Save & Load**: Export and import circuits via JSON text.  
    JSON形式での回路データの保存と読み込み。
*   **🛠 Zero Dependencies**: Runs entirely in a single HTML file. No build steps required.  
    依存ライブラリなし。1つのHTMLファイルだけで動作します。

## 📦 Components / 搭載部品

*   **Basic Gates**: AND, OR, NOT, NAND, XOR
*   **Input/Output**: Switch, Button, Keyboard, LED, RGB LED, 7-Segment Display, Buzzer
*   **Memory/CPU**: D/JK/SR Flip-Flops, 4-bit Counter, Decoder, RAM, ROM
*   **Visuals**: LED Matrix, Color Matrix

## 🎮 How to Use / 使い方

### Basic Controls / 基本操作

*   **Drag & Drop**: Drag parts from the sidebar to the canvas.  
    サイドバーから部品をドラッグ＆ドロップして配置。
*   **Wiring**: Click and drag from a pin (circle) to another pin.  
    ピン（丸い部分）からドラッグして配線。
*   **Select**: Drag the mouse on the background to select multiple parts.  
    背景をドラッグして範囲選択。
*   **Create IC**: Select parts -> Click "Create IC" button.  
    部品を選択して「⚡ 選択範囲をIC化」ボタンをクリック。

### Shortcuts / ショートカットキー

| Key | Action (English) | 動作 (日本語) |
| :--- | :--- | :--- |
| `Ctrl + Z` | Undo | 元に戻す |
| `Ctrl + C` | Copy Selection | 選択範囲をコピー |
| `Ctrl + V` | Paste Selection | 貼り付け |
| `Delete` | Delete Selection | 選択範囲を削除 |
| `Space` | Pan (Move View) | 視点移動（手のひらツール） |
| `E` | Edit Part (Label, ROM data, etc.) | 部品の編集（ラベル、ROMデータ等） |
| `C` | Change Wire Color | 配線色の変更（選択時） |

## 🚀 Installation / インストール方法

Simply download the `index.html` file and open it in any modern web browser.  
`index.html` をダウンロードし、ブラウザで開くだけで動作します。

1.  Clone the repository:
    ```bash
    git clone https://github.com/YOUR_USERNAME/web-logic-simulator.git
    ```
2.  Open `index.html` in Chrome, Firefox, Edge, or Safari.

## 📄 License

This project is licensed under the MIT License.
