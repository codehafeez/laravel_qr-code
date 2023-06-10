# PHP Laravel Example - QR Code

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.codehafeez.com/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/codehafeez/)

[![whatsapp](https://img.shields.io/badge/whatsapp-GREEN?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send?phone=923123349398)



```bash
CMD => composer create-project --prefer-dist laravel/laravel qr-code-example
CMD => cd qr-code-example


CMD => composer require simplesoftwareio/simple-qrcode

Update File
config/app.php => (update)
	
	'providers' => [
        	SimpleSoftwareIO\QrCode\QrCodeServiceProvider::class,
	],
    
    	'aliases' => [
        	'QrCode' => SimpleSoftwareIO\QrCode\Facades\QrCode::class,
	]



CMD => php artisan make:controller QrCodeController

Update File => Route::get('/qrcode', [QrCodeController::class, 'index']);

CMD => php artisan serve
```    

## Screenshots
![](https://raw.githubusercontent.com/codehafeez/laravel_qr-code/main/Screenshots/Output.png)


## 🔗 www.codehafeez.com
