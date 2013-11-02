---
layout: post
title: Githubda Depo oluşturma
---

Github anasayfasından Create a new repo

Sonrasında yerelde repo oluştur
Örnek olarak

$mkdir ~/start
<br />yerelde yenidizin oluşturur

$git init
dosyayı githubın anlayacağı dile cevir

<br />
$touch README
<br />
README isimli belge oluştur

$git add README
#README belgesini git için ekle

$git commit -m 'buraya mesajını yaz'
#commit et ve kısa bir mesaj yaz

$git remote add origin https://github.com/kullanici_adiniz/start.git
#Uzakta kaydedilecek yeri işaret eder

$git push origin master
#Uzak depodaki anadal(master)' gönder(push).
