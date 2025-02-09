# HtmlZipToWeb
-----------------------------------------------------------------
![Banner](https://github.com/Bohdan2505/HtmlZipToWeb/blob/main/app_banner.png?raw=true)

## Встановлення / Install

* Для встановлення застосунку завантаж apk файл з останнього релізу  
* To install the application, download the apk file from the latest release

## Created with Android Studio

## Примітка / Note
### Українською
Якщо у Вашому веб проєкті є потреба в завантаженні файлів на пристрій, то на даний момент в додатку реалізований JavascriptInterface лише для завантаження текстових файлів. Для коректного завантаження в JS використовуйте функцію This.requestDirectory(file_name, your_text_content), приклад:
```js
//IntegratedWebJSInterface - Javascript інтерфейс в додатку
const file_name = 'New.txt'
const txt_content = 'TEXT CONTENT'
if (IntegratedWebJSInterface) {
IntegratedWebJSInterface.requestDirectory(file_name, txt_content)
}
```
Автори розуміють, що це "милиці", але через брак досвіду іншого способу реалізації не знайшли. Якщо можеш допомогти вирішити проблему, повідом нас через Issue або на електронну адресу zhuravel.developer.communicate@gmail.com з зазначенням назви додатку "HtmlZipToWeb" в темі листа
### English
If your web project needs to download files to the device, the application currently implements the JavascriptInterface only for downloading text files. For correct uploading in JS, use the This.requestDirectory(file_name, your_text_content) function, for example:
```js
//IntegratedWebJSInterface - Javascript interface in app
const file_name = 'New.txt'
const txt_content = 'TEXT CONTENT'
if (IntegratedWebJSInterface) {
IntegratedWebJSInterface.requestDirectory(file_name, txt_content)
}
```
The authors realize that this is a crutch, but due to lack of experience, they have not found another way to implement it. If you can help solve the problem, please let us know via Issue or email zhuravel.developer.communicate@gmail.com with the name of the application “HtmlZipToWeb” in the subject line

-----------------------------------------------------------------
# Про застосунок [(English version)](#about-app)
![Logo](https://github.com/Bohdan2505/HtmlZipToWeb/blob/main/app_icon.png?raw=true)

-----------------------------------------------------------------
## Створюй веб-проєкти, стискай у .zip і переглядай прямо в додатку!

## Автори проєкту
Організатор розробки, автор ідеї - [Bohdan2505](https://github.com/Bohdan2505). Основний розробник - [systnager](https://github.com/systnager).
Є пропозиції або знайшли проблему? Створіть Issue або напишіть лист на електронну адресу zhuravel.developer.communicate@gmail.com з зазначенням назви додатку "HtmlZipToWeb" в темі 

## **Що це?** 
Це простий і зручний у використанні Android застосунок для перегляду HTML веб-проєктів, включно з файлами JavaScript, CSS та медіа. Він дозволяє відкривати локальні веб-карти (на базі Leaflet, OpenLayers, Mapbox) або звичайні HTML-сторінки, які упаковані в .zip архів. 

## **Чому цей додаток створено?**
На Android немає простої можливості відкривати HTML-файли з усіма супутніми файлами так само, як на Windows, Linux чи macOS. Наявні додатки з цим функціоналом переважно орієнтовані на веб-розробку і мають складний інтерфейс. Цей додаток пропонує легкий перегляд локальних веб-файлів без зайвих налаштувань. 

## **Як користуватись?**
### **1\. Створіть проєкт**
Розробіть веб-проєкт або зберіть необхідні файли, які можна переглядати у звичайному веб-браузері (без додаткових сервісів на кшталт Node.js або PHP). **Приклади:**  
*   веб-карти (Leaflet, OpenLayers, Mapbox);
*   прості HTML-сторінки.
**ВАЖЛИВО:** Головний файл, що буде відкриватися в застосунку має називатись **index.html**.
### **2\. Стисніть у .zip**
Помістіть файли у корінь .zip архіву для правильного відображення у додатку.
### **3\. Переглядайте у додатку**
Додайте архів і переглядайте свій веб-проєкт. 

## **Приватність**
*   Додаток не збирає та не передає жодних даних. Жодної передачі чи аналізу поза межами пристрою не відбувається. 
*   Геолокація доступна для навігації у ваших веб-картах і може бути вимкнена у налаштуваннях.

## **Умови використання**
Ви можете вільно використовувати додаток для особистих потреб, не порушуючи чинного законодавства. Розробники не надають жодних гарантій і не несуть відповідальності за використання додатка.

---------------------------------------------------------------------------




# **About app**
## Create web projects, compress them to .zip, and view them right in the app!

## Authors of the project
Development organizer, author of the idea - [Bohdan2505] (https://github.com/Bohdan2505). The main developer is [systnager](https://github.com/systnager).
Have any suggestions or found a problem? Create an Issue or write an email to zhuravel.developer.communicate@gmail.com with the name of the application “HtmlZipToWeb” in the subject line 

## **What is it?** 
This is a simple and easy-to-use Android application for viewing HTML web projects, including JavaScript, CSS, and media files. It allows you to open local web maps (based on Leaflet, OpenLayers, Mapbox) or regular HTML pages that are packed in a .zip archive. 

## **Why was this app created?** 
On Android, there is no easy way to open HTML files with all the associated files in the same way as on Windows, Linux, or macOS. Existing apps with this functionality are mostly focused on web development and have a complex interface. This app offers an easy way to browse local web files without any extra settings. 

## **How to use?**

### **1\. Create a project**
Develop a web project or collect the necessary files that can be viewed in a regular web browser (without additional services like Node.js or PHP).  
**Examples:**  
*   web maps (Leaflet, OpenLayers, Mapbox);
*   simple HTML pages.
**IMPORTANT:** The main the file to be opened in the application should be called **index.html**.
### **2\. Compress to .zip**
Place the files in the root of the .zip archive for proper display in the application.
### **3\. View in the application**
Add the archive and view your web project. 

## **Privacy**
*   The app does not collect or transmit any data. No transfer or analysis takes place outside the device.
*   Geolocation is available for navigation in your web maps and can be disabled in the settings.
    
## **Terms of use** 
You are free to use the application for your personal needs without violating the current legislation. The authors don't not provide any guarantees and is not responsible for the use of the application.

### Translated with DeepL.com (free version)
