Stack
Context
Share
Share with Flare
Docs

Stack

Context

Debug
Create Share
Docs

Ignition Settings
Docs
Editor

Idea
Theme
auto
Save settings
Settings will be saved locally in ~/.ignition.json.

include(/home/thegrowmorewin/public_html/laravel/vendor/composer/../../app/Http/Controllers/Adminapi.php): Failed to open stream: No such file or directory
ErrorException
PHP 8.1.33
9.42.0
include(/home/thegrowmorewin/public_html/laravel/vendor/composer/../../app/Http/Controllers/Adminapi.php): Failed to open stream: No such file or directory

Expand vendor frames
5 vendor frames
.unknown
0
is_a
32 vendor frames
 / 
home
 / 
thegrowmorewin
 / 
public_html
 / 
index
.php
 
: 52
[top]
 / 
home
 / 
thegrowmorewin
 / 
public_html
 / 
index
.php
 
: 52































|

| Composer provides a convenient, automatically generated class loader for

| this application. We just need to utilize it! We'll simply require it

| into the script here so we don't need to manually load our classes.

|

*/



require __DIR__.'/laravel/vendor/autoload.php';



/*

|--------------------------------------------------------------------------

| Run The Application

|--------------------------------------------------------------------------

|

| Once we have the application, we can handle the incoming request using

| the application's HTTP kernel. Then, we will send the response back

| to this client's browser, allowing them to enjoy our application.

|

*/



$app = require_once __DIR__.'/laravel/bootstrap/app.php';



$kernel = $app->make(Kernel::class);



$response = $kernel->handle(

    $request = Request::capture()

)->send();



$kernel->terminate($request, $response);

Request
https://thegrowmore-win.com/insert/withdrawal
POST
curl "https://thegrowmore-win.com/insert/withdrawal" \
   -X POST \
   -H 'x-https: 1' \
   -H 'cookie: XSRF-TOKEN=eyJpdiI6IjhmQ0ZjQzhUa0M5TTdwYmRsWXUzL3c9PSIsInZhbHVlIjoiYzJYbVFnWnJtaDVpWWl4NmtJWmM1WDdQRmFOU3owU0tSU0QycXFQNzJGUHp5MXkrN05VaDZpWnNkVHo1TklwSFFEREhyVGRRUHh0ZHJqenV2SmdZT2JiZW9VYVRYU3BZams1eXUrdDErczk0VDZpWG10Q0R0dVJFRWc3elVNSlkiLCJtYWMiOiI1NGM5ZDhjZjExNTRmZDJkMjY4NjliNmNmY2E1YTk2YThkMTJmZTU4YWU5ZTc4YTdiZDQ2MWVhYjExMWVjMzI3IiwidGFnIjoiIn0%3D; the_grow_more_session=eyJpdiI6Ijd4QzdMbHNFKzJNc2RLLzJHYkJkM0E9PSIsInZhbHVlIjoiaUN5VFloWDJvOWRCTjF3RksxcG9QejIzb1FXYVRzUXZSdktQZ2VlU3R0dFFvVHBEaVQ1dS8yS25LcDAxWmhLbXVaTUxKczM3RENYbFZLUFc2enFOcVhJOHlXOVF3SHlQTU1LYnp4ejRUSHI3bzFidmZqYmlhcTUwQi9iZzY4WWciLCJtYWMiOiJiYjZlNjliYzY5YTNlZGZiNDRkZDBiYjdjZGZjZDYyNmU1YzIyYWI0YTYzOTNiMTQ5NzZkOWEyMmRiNTI4ZDcwIiwidGFnIjoiIn0%3D' \
   -H 'accept-language: en-US,en;q=0.9' \
   -H 'accept-encoding: gzip, deflate, br, zstd' \
   -H 'referer: https://thegrowmore-win.com/withdraw' \
   -H 'sec-fetch-dest: document' \
   -H 'sec-fetch-user: ?1' \
   -H 'sec-fetch-mode: navigate' \
   -H 'sec-fetch-site: same-origin' \
   -H 'accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7' \
   -H 'user-agent: Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/138.0.0.0 Mobile Safari/537.36' \
   -H 'upgrade-insecure-requests: 1' \
   -H 'content-type: application/x-www-form-urlencoded' \
   -H 'origin: https://thegrowmore-win.com' \
   -H 'sec-ch-ua-platform: "Android"' \
   -H 'sec-ch-ua-mobile: ?1' \
   -H 'sec-ch-ua: "Not)A;Brand";v="8", "Chromium";v="138", "Google Chrome";v="138"' \
   -H 'cache-control: max-age=0' \
   -H 'content-length: 303' \
   -H 'connection: keep-alive' \
   -H 'host: thegrowmore-win.com' \
   -F '_token=H3cNxhhkdWgCRjqQScrmvBrL7EcSwaOsjWwbTANk' -F 'payment_gateway_type=3' -F 'min_withdraw_amount=null' -F 'amount=5000' -F 'wallet_balance=11725847.8' -F 'account_no=52200053273610' -F 'account_holder_name=Bir Chaudhary' -F 'bank_name=Bandhan' -F 'ifsc_code=BDBL0001614' -F 'upi_id=7892556702@ptaxis' -F 'mobile_no=7892556702' -F 'email=null' -F 'address=null' -F 'userid=null'


Headers
x-https
1

cookie
XSRF-TOKEN=eyJpdiI6IjhmQ0ZjQzhUa0M5TTdwYmRsWXUzL3c9PSIsInZhbHVlIjoiYzJYbVFnWnJtaDVpWWl4NmtJWmM1WDdQRmFOU3owU0tSU0QycXFQNzJGUHp5MXkrN05VaDZpWnNkVHo1TklwSFFEREhyVGRRUHh0ZHJqenV2SmdZT2JiZW9VYVRYU3BZams1eXUrdDErczk0VDZpWG10Q0R0dVJFRWc3elVNSlkiLCJtYWMiOiI1NGM5ZDhjZjExNTRmZDJkMjY4NjliNmNmY2E1YTk2YThkMTJmZTU4YWU5ZTc4YTdiZDQ2MWVhYjExMWVjMzI3IiwidGFnIjoiIn0%3D; the_grow_more_session=eyJpdiI6Ijd4QzdMbHNFKzJNc2RLLzJHYkJkM0E9PSIsInZhbHVlIjoiaUN5VFloWDJvOWRCTjF3RksxcG9QejIzb1FXYVRzUXZSdktQZ2VlU3R0dFFvVHBEaVQ1dS8yS25LcDAxWmhLbXVaTUxKczM3RENYbFZLUFc2enFOcVhJOHlXOVF3SHlQTU1LYnp4ejRUSHI3bzFidmZqYmlhcTUwQi9iZzY4WWciLCJtYWMiOiJiYjZlNjliYzY5YTNlZGZiNDRkZDBiYjdjZGZjZDYyNmU1YzIyYWI0YTYzOTNiMTQ5NzZkOWEyMmRiNTI4ZDcwIiwidGFnIjoiIn0%3D

accept-language
en-US,en;q=0.9

accept-encoding
gzip, deflate, br, zstd

referer
https://thegrowmore-win.com/withdraw

sec-fetch-dest
document

sec-fetch-user
?1

sec-fetch-mode
navigate

sec-fetch-site
same-origin

accept
text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7

user-agent
Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/138.0.0.0 Mobile Safari/537.36

upgrade-insecure-requests
1

content-type
application/x-www-form-urlencoded

origin
https://thegrowmore-win.com

sec-ch-ua-platform
"Android"

sec-ch-ua-mobile
?1

sec-ch-ua
"Not)A;Brand";v="8", "Chromium";v="138", "Google Chrome";v="138"

cache-control
max-age=0

content-length
303

connection
keep-alive

host
thegrowmore-win.com

Body
{
    "_token": "H3cNxhhkdWgCRjqQScrmvBrL7EcSwaOsjWwbTANk",
    "payment_gateway_type": "3",
    "min_withdraw_amount": null,
    "amount": "5000",
    "wallet_balance": "11725847.8",
    "account_no": "52200053273610",
    "account_holder_name": "Bir Chaudhary",
    "bank_name": "Bandhan",
    "ifsc_code": "BDBL0001614",
    "upi_id": "7892556702@ptaxis",
    "mobile_no": "7892556702",
    "email": null,
    "address": null,
    "userid": null
}


App
Routing
Controller
App\Http\Controllers\Adminapi@withdrawal_query

Middleware
Context
Versions
Php Version
8.1.33

Laravel Version
9.42.0

Laravel Locale
en

Laravel Config Cached
false
App Debug
true
App Env
local5
