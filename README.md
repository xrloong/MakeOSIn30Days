# MakeOSIn30Days
研讀《30 天打造 OS！作業系統自作入門》的筆記及源碼

## 目標

研讀《30 天打造 OS！作業系統自作入門》的筆記。

但在研讀過程中，覺得有些不足。
一來是，原書的對象，是沒有計算機背景者介紹的，這是作者的美意。但另一方面，對有背景者，在有些地方的說明就有點冗長，有些則不足。
二來是，基於 Windows ，會對於其它系統的使用者就比較不方便一點。
譬如，作者使用了自己開發的組譯器（nask.exe），對其它系統的使用者就比較就無法使用。
目前會考慮的平台為：
1. [ReactOS](https://reactos.org/)－一個致力於能執行 Windows 應用程式的作業系統。這裡用於執行原本的程式碼。
2. [Ubuntu](https://ubuntu.com/) Linux
3. macOS

## 環境設定

在開發過程式，要使用很多軟體或套件。

在 ReactOS 上，有一個應用程式，名為「程式管理員」，可以用安裝第三方工具：

在 Ubuntu 上，可使用內建套件管理工具：
```console
$ apt-get install {{套件名稱}}
```

在 macOS 上，可使用套件管理工具 [HomeBrew](https://brew.sh/index_zh-tw)
```console
$ bew install {{套件名稱}}
```

使用到以下軟體：
1. QEMU
   開源的虛擬機器。
2. 二進位檔瀏覽及編輯器
   1. xxd
      命令列指令。
   2. HexEdit

## 參考
繁體：《[30 天打造 OS！作業系統自作入門]》(https://www.tenlong.com.tw/products/9789866348297)
簡體：《[30天自制操作系统]》(https://www.tenlong.com.tw/products/9787115287960)

[《30天自制操作系统》源码中文版](https://github.com/yourtion/30dayMakeOS)
[《30天自制操作系统》笔记](https://www.cnblogs.com/yucloud/category/1472969.html)

