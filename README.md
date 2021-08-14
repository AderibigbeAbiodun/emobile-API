# emobile-API
This API Allow reseller to start their own VTU Business and Developer for their projects  Fast and Reliable API End-point

  <h2>Verify API Key Endpoint</h2>
    <a href="https://emobilesms.com/api/verify/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx">
        https://emobilesms.com/api/verify/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx
    </a>

  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
        "status":200,
        "result":"Valid ApiKey (OK)"
       }]
     }
  </pre>


<h2>Login Endpoint</h2>
<a href="https://emobilesms.com/api/login/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/email/mail@exmple.com/password/12345">
  https://emobilesms.com/api/login/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/email/mail@exmple.com/password/12345
</a>

  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
        "usertoken":"610D7xxxxxxx",
        "status":200,
        "result":"Successfully"
       }]
     }
  </pre>
  

<h2>Buy Airtime Endpoint</h2>
<a href="https://emobilesms.com/api/airtime/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/61008xxxxxx/network/MTN/amount/100/recipient/080123456789">
  https://emobilesms.com/api/airtime/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/61008xxxxxx/network/MTN/amount/100/recipient/080123456789
</a>

  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
        "refno":929xxxxxxxx,
        "status":200,
        "result":"Successfully"
       }]
     }
  </pre>
  
  <h2>Buy Data Bundle Endpoint</h2>
  <a href="https://emobilesms.com/api/data/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxx/network/MTN/plan/6100xxxxxxx/recipient/080123456789">
    https://emobilesms.com/api/data/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxx/network/MTN/plan/6100xxxxxxx/recipient/080123456789
  </a>
  
  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
        "refno":"929xxxxxx",
        "status":200,
        "result":"Successfully"
       }]
     }
  </pre>
  
   <h2>Check Balance Endpoint</h2>
  <a href="https://emobilesms.com/api/balance/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx/">
    https://emobilesms.com/api/balance/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx/
  </a>
  
  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
        "wallet":"4661.5",
        "sms":"5000",
        "status":200,
        "result":"Successfully"
       }]
     }
  </pre>
  
  
  <h2>Reseller Register New Users Endpoint</h2>
  <a href="https://emobilesms.com/api/register/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx/email/xxxxxxxx@xxx.xxx/username/xxxxx xxx/password/xxxxxx/country/xxxxxx/currency/xxxx">
  https://emobilesms.com/api/register/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx/email/xxxxxxxx@xxx.xxx/username/xxxxx xxx/password/xxxxxx/country/xxxxxx/currency/xxxx
  </a>
  
  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
        "status":200,
        "result":"Successfully"
       }]
     }
  </pre>
  
  <h2>Reseller Login Users Endpoint</h2>
  <a href="https://emobilesms.com/api/login-sub-user/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx/email/xxxxxxxx@xxx.xxx/password/xxxxx">
https://emobilesms.com/api/login-sub-user/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx/email/xxxxxxxx@xxx.xxx/password/xxxxx
  </a>
  
  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
        "session":"610AXXXXXX",
        "status":200,
        "result":"Successfully"
       }]
     }
  </pre>
  
   <h2>Reseller Get Single Users Endpoint</h2>
  <a href="https://emobilesms.com/api/user-data/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx/userid/6100xxxxxxxx">
  https://emobilesms.com/api/user-data/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx/userid/6100xxxxxxxx
  </a>
  
  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
          "userid":"1",
          "usertoken":"xxxxxxxx",
          "fullname":"xxxxxx xxxx",
          "email":"xxxxxxxx@xxxx.xxx",
          "phone":"xxxxxxxxxx",
          "state":"xxx",
          "address":"xxxxxxx",
          "country":"xxxxxxxx",
          "currency":"x",
          "account_type":"xxxxxx",
          "accountstatus":"xxxxx",
          "wallet_amount":"xxx",
          "sms_bal":"xxx",
          "createdate":"xxxxxxxx",
          "status":200,
          "result":"Successfully"
          }]
        }
  </pre>
  
  <h2>Reseller Get All Users Endpoint</h2>
  <a href="https://emobilesms.com/api/get-users/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx">
    https://emobilesms.com/api/get-users/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx
  </a>
  
  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
          "userid":"1",
          "usertoken":"xxxxxxxx",
          "fullname":"xxxxxx xxxx",
          "email":"xxxxxxxx@xxxx.xxx",
          "phone":"xxxxxxxxxx",
          "state":"xxx",
          "address":"xxxxxxx",
          "country":"xxxxxxxx",
          "currency":"x",
          "account_type":"xxxxxx",
          "accountstatus":"xxxxx",
          "wallet_amount":"xxx",
          "sms_bal":"xxx",
          "createdate":"xxxxxxxx",
          "status":200,
          "result":"Successfully"
          }]
        }
  </pre>
  
   <h2>Reseller Data Endpoint</h2>
  <a href="https://emobilesms.com/api/reseller-data/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx">
    https://emobilesms.com/api/reseller-data/apikey/2034caa39xxxxxxxxxxxxxxxxxxxxxxxxx/usertoken/6100xxxxxxxx
  </a>
  
  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
          "userid":"1",
          "usertoken":"xxxxxxxx",
          "fullname":"xxxxxx xxxx",
          "email":"xxxxxxxx@xxxx.xxx",
          "phone":"xxxxxxxxxx",
          "state":"xxx",
          "address":"xxxxxxx",
          "country":"xxxxxxxx",
          "currency":"x",
          "account_type":"xxxxxx",
          "accountstatus":"xxxxx",
          "website":"xxx",
          "logo":"xxx",
          "createdate":"xxxxxxxx",
          "status":200,
          "result":"Successfully"
          }]
        }
  </pre>

