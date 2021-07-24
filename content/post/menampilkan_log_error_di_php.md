---
author: "Darwisy Alfarizi"
title: "Menampilkan Log Error di PHP Ketika: The localhost page isn’t working"
date: "2021-05-11"
description: "Menampilkan Log Error di PHP Ketika: The localhost page isn’t working"
tags:
- php

categories:
- error
- Program
draft: false		
---

## Menampilkan Log Error di PHP Ketika: The localhost page isn’t working

### Bagaimana cara menampilkannya?



#### 1. Tambahkan kode di file php yang error 

    ini_set("display_errors","1");
	error_reporting(E_ALL);

#### 2. Ordered List

1. Buka xampp
2. Pilih logs pada apache
3. Pilih Apache(error.log)


#### 3. Setting php.ini di xampp

1. Buka xampp
2. Pilih config
3. Pilih Apache(php.ini)
4. Cari display_errors = off
5. Ganti Jadi on
    
