<h1 align="center">Welcome to Qrcode Maker Project 👋</h1>

# Qrcode Maker

In this project, we will write a qrcode creation program using Python, which can be used by giving the website address or text or even the Wi-Fi password.

## Modules 

In this project, we used the qrcode module to run this program with its help

```python
import qrcode as qr
```

## Usage

```python
img = qr.make("YourAddress")
img.save('test1.png')
```

In this short project, we send the desired address or text using the make command and save it with the save command


How to address Wi-Fi in a qrcode
```python
img = qr.make("WIFI:S:wifiname;T:WPA2;P:password;")
```

## Result

This project was written by Majid Tajanjari and the Aiolearn team, and we need your support!❤️

# Qrcode ساخت

در این پروژه با استفاده از پایتون یک برنامه ساخت qrcode می نویسیم که با دادن آدرس وب سایت یا متن یا حتی رمز وای فای می توان از آن استفاده کرد.

## ماژول ها

در این پروژه از ماژول qrcode برای اجرای این برنامه به کمک آن استفاده کردیم

```python
import qrcode as qr
```

## نحوه استفاده

```python
img = qr.make("YourAddress")
img.save('test1.png')
```

در این پروژه کوتاه با استفاده از دستور make آدرس یا متن مورد نظر را ارسال کرده و با دستور save ذخیره می کنیم


نحوه آدرس دهی وای فای در یک qrcode
```python
img = qr.make("WIFI:S:wifiname;T:WPA2;P:password;")
```

## نتیجه

این پروژه توسط مجید تجن جاری و تیم Aiolearn نوشته شده است و ما به حمایت شما نیازمندیم!❤️