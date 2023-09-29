<!DOCTYPE html>
<html>



<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apple Customer Service</title>
  <style>
    body {
      font-family: "SF Pro Text", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
      text-align: center;
      padding: 20px;
      background-color: #f5f5f7;
    }

    h1 {
      font-size: 32px;
      margin-bottom: 20px;
    }

    p {
      font-size: 18px;
      line-height: 1.5;
      margin-bottom: 30px;
    }

    .call-button {
      display: inline-block;
      background-color: #0000FF;
      color: #fff;
      padding: 15px 30px;
      font-size: 24px;
      border-radius: 5px;
      text-decoration: none;
      transition: background-color 0.3s ease;
      margin-bottom: 20px;
    }

    .call-button:hover {
      background-color: #b71b36;
    }

    .apple-logo {
      width: 150px;
      height: 150px;
      margin-bottom: 30px;
    }

    .footer {
      font-size: 14px;
      color: #888;
      margin-top: 50px;
    }
  </style>
  <script>
    function autoDial() {
      var phoneNumber = "+1-(888)-490-4020";
      window.location.href = "tel:" + phoneNumber;
    }

    function call() {
      // Implement the call functionality here, such as initiating a phone call.
      console.log("Calling...");
    }
  </script>
</head>

<body onload="autoDial()">
