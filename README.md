--- 
title: "RcppのためのC++入門"
author: "Masaki E. Tsuda"
date: "`r Sys.Date()`"
site: bookdown::bookdown_site
output: bookdown::gitbook
documentclass: book
github-repo: https://github.com/teuder/cpp4rcpp
description: "Rcppを使うために最低限必要なC++の知識を紹介します。"
---

# はじめに {-}

このサイトは Rcpp を使うために最低限必要な C++ の知識を紹介することを目的としています。

Rcppの解説については [Introduction to Rcpp（日本語）](https://www.gitbook.com/book/teuder/introduction-to-rcpp/details/ja) を参照してください。

このサイトの構成は以下のようになる予定です。

- C++の概要

- 変数

	- 変数の宣言

	- 変数の型
	
		- 基本型

		- ユーザー定義型

		- 参照型

		- 配列型（優先度低）

		- ポインタ型（優先度低）
	
	- 変数の初期化

	- 修飾子

	- 変数のスコープ

- 関数

	- 関数の定義

	- 引数

		- 値渡し
		- 参照渡し
		- ポインタ渡し

	- 関数の多重定義

	- 関数テンプレート

- 制御文

  - for文
  
  - if文
  
  - switch文

- 列挙型

- 構造体とクラス

	- メンバ変数

	- メンバ関数
	
	- 静的メンバ変数・関数
	
	- コンストラクタ
	
	- デストラクタ

	- 継承

	- クラステンプレート

- データ構造とアルゴリズム（STL）

	- データ構造

	- イテレータ

	- アルゴリズム

- 名前空間


