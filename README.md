# emobile-API
This API Allow reseller to start their own VTU Business and Developer for their projects  Fast and Reliable API End-point

  <h2>Verify API Key Endpoint</h2>
    <a href="https://emobilesms.com/api/verify/apikey/2034caa3901d0858fc5fadfaf06f046b385ebcff">
        https://emobilesms.com/api/verify/apikey/2034caa3901d0858fc5fadfaf06f046b385ebcff
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
<a href="https://emobilesms.com/api/login/apikey/2034caa3901d0858fc5fadfaf06f046b385ebcff/email/aderibigbebiodun@gmail.com/password/8307637653">
  https://emobilesms.com/api/login/apikey/2034caa3901d0858fc5fadfaf06f046b385ebcff/email/aderibigbebiodun@gmail.com/password/8307637653
</a>

  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
        "usertoken":"610080EC9D3C3",
        "status":200,
        "result":"Successfully"
       }]
     }
  </pre>
  

<h2>Buy Airtime Endpoint</h2>
<a href="https://emobilesms.com/api/airtime/apikey/2034caa3901d0858fc5fadfaf06f046b385ebcff/usertoken/610080EC9D3C3/network/Airtel/amount/100/recipient/08120204950">
  https://emobilesms.com/api/airtime/apikey/2034caa3901d0858fc5fadfaf06f046b385ebcff/usertoken/610080EC9D3C3/network/Airtel/amount/100/recipient/08120204950
</a>

  <h3>RESPONSE</h3>
  <pre>
    {
      "response":[
      {
        "refno":92988827,
        "status":200,
        "result":"Successfully"
       }]
     }
  </pre>




