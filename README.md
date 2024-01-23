# <img src="app/src/main/ic_launcher-playstore.png" width="60px"> LIME: Adkiller for LINE

[![Latest Release](https://img.shields.io/github/v/release/Chipppppppppp/LIME?label=latest)](//github.com/Chipppppppppp/LIME/releases/latest)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 概要

This is an Xposed Module to clean [**LINE**](//line.me). 

LINE を掃除する Xposed Module です。

## インストール

### Root 端末

1. [**Magisk**](//github.com/topjohnwu/Magisk) 及び [**LSPosed**](//github.com/LSPosed/LSPosed) をインストール
2. [Releases](//github.com/Chipppppppppp/LIME/releases/latest) から APK ファイルを DL & インストール
> [!NOTE]
> Play プロテクトによりブロックされた場合、<kbd>詳細</kbd>から<kbd>インストールする</kbd>をタップ
3. LSPosed のモジュールから LIME に移動し、<kbd>モジュールの有効化</kbd>と LINE アプリにチェックを入れる

### 非 Root 端末

1. [**LSPatch**](//github.com/LSPosed/LSPatch) をインストール
2. [Releases](//github.com/Chipppppppppp/LIME/releases/latest) から APK ファイルをDL
3. [APKMirror](//www.apkmirror.com/) などから LINE apk を DL
4. 指示に従って LINE apk に LIME apk をパッチする
5. パッチされた LINE apk をインストール

## 機能

- 画面下部の \[VOOM]・\[ウォレット] アイコンの削除
- 広告の削除
- WebView (アプリ内ブラウザ) を規定のブラウザにリダイレクト

## 既知の問題

- 稀にホームタブの広告の場所に余白が残る

## 問題の報告

新たなバグや修正方法を見つけた場合は、[報告](//github.com/Chipppppppppp/LIME/issues/new/choose)をお願いします。
