# Paypal Integration in laravel 5.8
<hr>
Please follow the steps to run the above project.If you want integration details please read <b>"users guide"</b> file which is in this project.<br>

1. Copy the clone link or you can download zip. <br>
2. Go to xampp/htdocs open cmd window nad type below command : <br>
    git clone https://github.com/ashish744737/paypal-gateway.git
3. Go to project folder and within project open cmd and update composer : <br>
    update composer
4. Create <b>.env</b> in root directory same as <b>.env.example</b> and set <b>APP_URL=http://localhost/paypal-gateway</b> or as per your    localhost environment.<br>
5.Generate <b>APP_KEY</b> by using following command.<br>
    php artisan key:generate
6.Go to .env file and set database details <br>
    DB_CONNECTION=mysql<br>
    DB_HOST=127.0.0.1<br>
    DB_PORT=3306<br>
    DB_DATABASE=database name<br>
    DB_USERNAME=database username<br>
    DB_PASSWORD=database password<br>
7.Go to Config/paypal.php and add your paypal creadentials also you add paypal sandbox details in .env file as follows: <br>
    PAYPAL_MODE=sandbox<br>
    PAYPAL_SANDBOX_API_USERNAME=<br>
    PAYPAL_SANDBOX_API_PASSWORD=<br>
    PAYPAL_SANDBOX_API_SECRET=<br>
    PAYPAL_CURRENCY=INR<br>
    PAYPAL_SANDBOX_API_CERTIFICATE=<br>
8.Now you can run your project.
<hr>
Ashish Avinash Pasekar<br>
ashish.pasekar@gmail.com
    
    

