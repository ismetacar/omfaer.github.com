---
layout: post
title: Githubda Depo oluşturma
---

Github anasayfasından Create a new repo

Sonrasında yerelde repo oluştur
Örnek olarak

$mkdir ~/start
<br /> yerelde yenidizin oluşturur
$git init
<br /> dosyayı githubın anlayacağı dile cevir
$touch README
<br /> README isimli belge oluştur
$git add README
<br />README belgesini git için ekle
$git commit -m 'buraya mesajını yaz'
<br />commit et ve kısa bir mesaj yaz
$git remote add origin https://github.com/kullanici_adiniz/start.git
<br />Uzakta kaydedilecek yeri işaret eder
$git push origin master
<br />Uzak depodaki anadal(master)' gönder(push).
