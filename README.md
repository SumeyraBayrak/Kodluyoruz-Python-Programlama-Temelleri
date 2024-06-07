#  **Kodluyoruz Python Programlama Temelleri**

Bu proje, Python programlama diline yeni başlayanlar için temel kavramları öğrenmek ve siber güvenlik alanına giriş yapmak isteyenler için özel olarak hazırlanmıştır. Siber güvenlik dünyasına adım atarken Python'un temel yeteneklerini kazanmak, sadece programlama becerilerinizi geliştirmekle kalmayacak, aynı zamanda siber güvenlikteki temel kavramları da anlamanıza yardımcı olacaktır.

Bu depodaki kaynaklar, size Python programlama dilini öğrenirken aynı zamanda siber güvenlik alanında kritik bilgileri sunar. Proje, interaktif bir öğrenme deneyimi sunmak amacıyla Jupyter Notebook kullanılarak oluşturulmuştur. Bu sayede, hem kod yazma becerilerinizi geliştirecek hem de siber güvenlik dünyasına dair temel kavramları daha derinlemesine anlayabileceksiniz.

Projenin amacına uygun bir şekilde tasarlandığına ve Python ile siber güvenlik konularını öğrenmek isteyenlere değerli bir kaynak sunduğuna inanıyorum. 🌟 IBM ile Kodluyoruz: CyberStart Programı, Python programlama dilini öğrenmek ve siber güvenlik alanında temel bilgiler edinmek isteyenleri etkileşimli bir deneyime davet ediyor. 🛡️ Bu yolculukta başarılar dilerim! 🚀


![Python Resmi](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/240px-Python-logo-notext.svg.png)

A brief description of what this project does and who it's for

##  **İçerik**

- **Giriş**
  - [Programlama Nedir?](https://github.com/SumeyraBayrak/Kodluyoruz-Python-Programlama-Temelleri/blob/main/Kodluyoruz-Python-Programlama-Temelleri/Python-1/1-%20Giri%C5%9F/1-programlama-nedir.ipynb)
  - [Temel Veri Tipleri](https://github.com/SumeyraBayrak/Kodluyoruz-Python-Programlama-Temelleri/blob/main/Kodluyoruz-Python-Programlama-Temelleri/Python-1/1-%20Giri%C5%9F/2-temel-veri-tipleri.ipynb)
  - [Değişken Atama](#değişken-atama)
  - [Operatörler ve İfadeler](#operatörler-ve-İfadeler)

- **String'ler**
  - [String Nedir?](#string-nedir)
  - [Stringler Üzerinde Operatörler](#stringler-üzerinde-operatörler)
  - [Stringlerde İndexleme](#stringlerde-İndexleme)
  - [Stringlerde Casting](#stringlerde-casting)

- **Input**
  - [Input Fonsiyonu Nedir?](#input-fonsiyonu-nedir)

- **Koda Yorum Ekleme**
  - [Kod Bloğuna Nasıl Yorum Eklenir?](#kod-bloğuna-nasıl-yorum-eklenir)

- **Koda Durumsallık Katmak**
  - [Sayısal Verilerde Karşılaştırma](#sayısal-verilerde-karşılaştırma)
  - [Stringlerde Karşılaştırma](#stringlerde-karşılaştırma)
  - [Mantıksal Operatörler](#mantıksal-operatörler)
  - [Short-circuit](#short-circuit)
  - [Short-circuit Olmayan Mantıksal Operatörler](#short-circuit-olmayan-mantıksal-operatörler)

- **Koşullar**
  - [Koşullu İfadeler (if-else-elif) Kullanımı](#koşullu-ifadeler-if-else-elif-kullanımı)
  - [Ternary Conditionals](#ternary-conditionals)

- **Döngüler**
  - [Döngüler Kullanımı](#döngüler-kullanımı)
  - [While Döngüsü](#while-döngüsü)
  - [For Döngüsü](#for-döngüsü)
  - [Continue ve Break İfadeleri](#continue-ve-break-ifadeleri)

- **Non-Scalar Veri Tipleri**
  - [Liste Nedir?](#liste-nedir)
  - [Tuple Nedir?](#tuple-nedir)
  - ['in' Anahtar Kelimesi](#in-anahtar-kelimesi)
  - [Dictionary Nedir?](#dictionary-nedir)
  - [Set Nedir?](#set-nedir)
  - [Non-scalar Veri Tiplerinde For](#non-scalar-veri-tiplerinde-for)
  - [Split-Join](#split-join)
  - [List Comprehension](#list-comprehension)
  - [Variable Unpacking](#variable-unpacking)
  - [Enumerate-Zip](#enumerate-zip)

- **Fonksiyonlar**
  - [Fonksiyon Nedir?](#fonksiyon-nedir)
  - [return Kullanımı](#return-kullanımı)
  - [Comment-Fonksiyon](#comment-fonksiyon)
  - [Birden Fazla Değer Döndürme/Input İçerme](#birden-fazla-değer-döndürmeinput-içerme)
  - [Predefined Parameters](#predefined-parameters)
  - [Update Input](#update-input)
  - [First Class Function](#first-class-function)
  - [For-Function](#for-function)

- **Underscore Placeholder**
  - [Underscore Placeholder Nedir?](#underscore-placeholder-nedir)

- **F-string**
  - [F-string Nedir?](#f-string-nedir)

- **Proje**
  - [Soru 1](#soru-1)
  - [Soru 2](#soru-2)

- **Python Uygulama**
  - [Öklid Mesafesinin Hesaplanması](#soru-1)

##   **Teşekkürler**

Bu projenin geliştirilmesinde aşağıdaki kaynaklar ve kişiler önemli katkılar sağladı:

- [Python Eğitimleri](https://academy.patika.dev/tr/courses/python-temel/coderbyte-challenge) - Patika.dev'deki Python Temel eğitimi, projenin temelini oluşturan Python bilgilerini sağladı ve bu bilgileri pratik yapma fırsatı sundu. Eğitimdeki dersler ve videolar, projenin geliştirilmesine büyük ölçüde katkı sağladı.
- Engin Deniz Alpman - Patika.dev'deki Python Temel eğitiminden aldığım bilgilerle projeyi geliştirirken, Engin Deniz Alpman'ın öğretim tarzı ve içeriği benim için rehber niteliğinde oldu. Kendisine teşekkür ederim.

- **Python Eğitimleri**: Python temel konularını öğrenmek ve pratik yapmak için [Patika.dev Python Temel](https://academy.patika.dev/tr/courses/python-temel/coderbyte-challenge) eğitimlerine göz atabilirsiniz. Bu eğitimlerde dersler ve videolar bulunmaktadır.
