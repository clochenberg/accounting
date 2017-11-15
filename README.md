![SpecTech Accounting](http://www.spectech-it.co.za/assets/images/accounting-logo-400x156.png)
#### _Version 1.5.5_

Spectech Accounting is a self-hosted open source application for managing your invoices, clients and payments.    
For more information visit __[spectech-it.co.za](http://www.spectech-it.co.za)__ or try the __[demo](http://demoacc.spectech-it.co.za/)__.

---

### Quick Installation

1. Download the latest version [from the SpecTech Accounting website](http://www.spectech-it.co.za/downloads.html).
2. Extract the package and copy all files to your webserver / webspace.
3. Make a copy of the `ipconfig.php.example` file and rename this copy to `ipconfig.php`.
4. Open the `ipconfig.php` file and add your URL like specified in the file.
5. Open `http://your-accounting-domain.com/index.php/setup` and follow the instructions.


_Notice: Please download SpecTech Accounting from our [website](http://www.spectech-it.co.za/downloads.html) only as the packages contain additional needed components. If you are a developer, read the [development guide](DEVELOPMENT.md)._

#### Remove `index.php` from the URL

If you want to remove `index.php` from the URL, follow these instructions. However, this is an optional step and not a requirement. If it's not working correctly, take a step back and use the application with out removing that part from the URL.

1. Make sure that [mod_rewrite](https://stackoverflow.com/questions/869092/how-to-enable-mod-rewrite-for-apache-2-2/5758551#5758551) is enabled on your web server.
2. Set the `REMOVE_INDEXPHP` setting in your `ipconfig.php` to `true`.
3. Rename the `htaccess` file to `.htaccess`

If you want to install SpecTech Accounting in a subfolder (e.g. `http://your-accounting-domain.com/accounting/`) you have to change the `ipconfig.php` and `.htaccess` file. The instructions can be found within the files.

---

### Support / Development / Chat

Need some help or want to talk with other about SpecTech Accounting? Follow these links to get in touch.

[![Website](https://img.shields.io/badge/Help-Website-red.svg)](http://www.spectech-it.co.za/contact.html)  
[![Email](https://img.shields.io/badge/Help-Email-red.svg)](mailto:info@spectech-it.co.za) 

---

### Security Vulnerabilities

If you discover a security vulnerability please send an e-mail to info@spectech-it.co.za before disclosing the vulnerability to the public.
All security vulnerabilities will be promptly addressed.

---

> The name 'SpecTech Accounting' and the SpecTech logo are both copyright by Christo Lochenberg and www.spectech-it.co.za
and their usage is restricted! For more information visit http://www.spectech-it.co.za/license.html
