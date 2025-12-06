# Canvas Downloader (Numbered Version)

> **Note:** This is a fork of the original [Canvas Downloader](https://github.com/santriseus/canvas-downloader).

## 🇬🇧 English Description

### ⚡ Key Difference in this version
The main change in this fork is the **file naming convention** inside the downloaded ZIP archive.
Instead of `canvas_1.png`, `canvas_2.png`, files are saved as a clean numbered sequence with leading zeros:
*   **`001.png`**
*   **`002.png`**
*   **`003.png`**
*   ...

This makes it easier to sort and process sequences of images (frames).

### Original Description
Extension helps detect if canvas is used at the web page and allows to export and download canvas content in multiple formats.
Extension could be helpful if creator of the web site disabled the canvas context menu with "Save As" option.

You could see the counter with the number of detected canvas elements in the extension icon, if any canvas detected.
Sometimes the counter at the icon could be different from the real amount of available canvas elements, because of the security concerns like "Cross-Origin Resource Sharing" policies applied to source images.

### 📦 How to Install (from source)
Since this is a custom fork, you need to install it manually:

1.  Clone this repository or download the ZIP.
2.  Open Google Chrome and navigate to `chrome://extensions/`.
3.  Enable **Developer mode** (toggle switch in the top right corner).
4.  Click **Load unpacked** (top left).
5.  Select the folder containing this extension.

---

## 🇷🇺 Описание на русском

### ⚡ Главное отличие этой версии
Основное изменение в этом форке касается **именования файлов** внутри скачиваемого ZIP-архива.
Вместо стандартных имен вида `canvas_1.png`, `canvas_2.png`, файлы сохраняются с удобной нумерацией и ведущими нулями:
*   **`001.png`**
*   **`002.png`**
*   **`003.png`**
*   ...

Это значительно упрощает сортировку и дальнейшую обработку последовательностей изображений (кадров).

### Описание оригинала
Расширение помогает обнаружить использование элемента canvas на веб-странице и позволяет экспортировать и сохранять его содержимое в различных форматах.
Это полезно, если создатель сайта отключил контекстное меню canvas (опцию "Сохранить как").

На иконке расширения отображается счетчик найденных элементов canvas. Иногда это число может отличаться от реального количества доступных элементов из-за политик безопасности браузера (CORS), применяемых к исходным изображениям.

### 📦 Как установить (вручную)
Так как это модифицированная версия, её нужно установить вручную:

1.  Скачайте этот репозиторий (или ZIP-архив с кодом).
2.  Откройте Google Chrome и перейдите по адресу `chrome://extensions/`.
3.  Включите **Режим разработчика** (переключатель в правом верхнем углу).
4.  Нажмите кнопку **Загрузить распакованное расширение** (Load unpacked) в левом верхнем углу.
5.  Выберите папку, в которую вы скачали это расширение.

---

### Credits / Авторство
Original extension by [santriseus](https://github.com/santriseus).
Original available at [Chrome Store](https://chrome.google.com/webstore/detail/canvas-downloader-find-an/dgfcgcafnnbdpojemnkiiilnnghebgja).
