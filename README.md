# Personal-Vpn
راه اندازی سرور فیلترشکن شخصی

از این سرور فیلترشکن ها میتوانید برای ترید و سایت های که ip ایران را محدود کردن استفاده کنید

ساخت یک سرور با سیستم عامل: Centos 7 x86 (or) Centos 7 x64

لاگین کردن به سرور با نرم افزار putty و اجرای دستور زیر:

cd /tmp/ && yum install git -y && git clone https://github.com/Pouriyaasakereh/Personal-Vpn.git && cd Personal-Vpn/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh 

دستورات زیر برای اضافه کردن کاربر به سرور:

useradd [username] - 
passwd [username]
