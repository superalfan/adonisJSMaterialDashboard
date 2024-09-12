# adonisJSMaterialDashboard
Memadukan AdonisJS 6 dan Material Dashboard 2

Saya gabungkan Framework AdonisJS V6 dengan Material Black Dashboard Versi Free

silahkan download versi free ini di repository berikut : https://github.com/superalfan/adonisJSMaterialDashboard

git clone https://github.com/superalfan/adonisJSMaterialDashboard

masuk ke directory 

cd adonisjsblackdashboard

    npm install

atau bisa menggunakan 

    yarn

karena versi free ini belum di integrasikan dengan database, silahkan isi sembarang
atau tetap biarkan dengan yang sudah terisis seperti berikut

    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_USER=userone
    DB_PASSWORD=secret
    DB_DATABASE=adonisjsblackdashboard



//===========================================================================================
Saya juga menyediakan Framework ini untuk versi Pro yang terdiri dari

Admin Dashboard    
    Admin Login + captcha
    Admin Register + captcha
    Forgot Password 
    Confirm Email with OTP

User Dashboar
    User Login + captcha
    User Register + captcha
    Forgot Password
    Confirm Email with OTP
    Logout


App
    User Login + captcha
    User Register + captcha
    Forgot Password
    Confirm Email with OTP

    App Dashboard 5 Tab Kosong (siap dijadikan apapun terserah User)


untuk database versi Pro
Table user dan admin ada di satukan di table user dan admin dibedakan di kolom role dan secara default role sebagai user

Koneksi antara app dan backend hanya untuk user tidak disediakan untuk admin
koneksi ke app menggunakan auth token
