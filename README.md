<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            background-color: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            width: 350px;
            text-align: center;
        }

        .container h2 {
            margin-top: 0;
            margin-bottom: 20px;
            color: #333;
        }

        .container button {
            display: block;
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }

        .container button:hover {
            background-color: #0056b3;
        }
    </style>
</head>

<body>
    <div class="container">
        <h2>Welcome</h2>
        <button onclick="location.href='login_doctor.html'">Login as Doctor</button>
        <button onclick="location.href='login_patient.html'">Login as Patient</button>
        <button onclick="location.href='login_pharmacist.html'">Login as Pharmacist</button>
    </div>
</body>

</html>
