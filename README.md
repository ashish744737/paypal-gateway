# Paypal Integration in laravel 5.8
<hr>
Please follow the steps to run the above project.If you want integration details please read <b>"users guide"</b> file which is in this project.<br>

1. Copy the clone link or you can download zip. <br>
2. Go to xampp/htdocs open cmd window nad type below command : <br>
    git clone https://github.com/ashish744737/paypal-gateway.git
3. Go to project folder and within project open cmd and update composer : <br>
    update composer
4. Create <b>.env</b> in root directory same as <b>.env.example</b> and set <b>APP_URL=http://localhost/paypal-gateway</b> or as per        your localhost environment.<br>
5. Generate <b>APP_KEY</b> by using following command.<br>
    <b>php artisan key:generate</b><br>
6. Go to .env file and set database details <br>
    <b>DB_CONNECTION=mysql</b><br>
    <b>DB_HOST=127.0.0.1</b><br>
    <b>DB_PORT=3306</b><br>
    <b>DB_DATABASE=database name</b><br>
    <b>DB_USERNAME=database username</b><br>
    <b>DB_PASSWORD=database password</b><br>
7. Go to <b>Config/paypal.php</b> and add your paypal creadentials also you add paypal sandbox details in <b>.env</b> file as follows: <br>
    <b>PAYPAL_MODE=sandbox</b><br>
    <b>PAYPAL_SANDBOX_API_USERNAME=</b><br>
    <b>PAYPAL_SANDBOX_API_PASSWORD=</b><br>
    <b>PAYPAL_SANDBOX_API_SECRET=</b><br>
    <b>PAYPAL_CURRENCY=INR</b><br>
    <b>PAYPAL_SANDBOX_API_CERTIFICATE=</b><br>
8. Now you can run your project.
<hr>
<b>Ashish Avinash Pasekar</b><br>
ashish.pasekar@gmail.com
    
    

