---
layout: post
title:  "Scanning barcode images"
date:   2015-01-14 11:23:00
tags:   ruby, barcode
---
Yesterday I was playing with [ZXing_cpp][1]{:target="_blank"} to see if it perform better than zbar.

I did some tests with images generated by some application and some photos I took.

First, all the tests that I did with zbar passed successfully with ZXing, plus some photos I took. In fact the photos must be in a good quality and I had to crop it to display only the barcode. Some shaking hands photos wasn't recognized.

[1]:https://github.com/glassechidna/zxing_cpp.rb
