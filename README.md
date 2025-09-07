<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Redock</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #121212;
      color: white;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px;
      background-color: #1e1e1e;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 10;
    }
    nav {
      display: flex;
      gap: 20px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 10px 15px;
      border-radius: 8px;
      transition: background-color 0.3s;
    }
    nav a:hover {
      background-color: #333;
    }
    .feed {
      margin-top: 80px;
      padding: 20px;
      display: flex;
      flex-direction: column;
      gap: 30px;
    }
    .post {
      background-color: #1e1e1e;
      padding: 15px;
      border-radius: 12px;
    }
    .post video, .post img {
      width: 100%;
      border-radius: 10px;
    }
    .actions {
      display: flex;
      justify-content: space-around;
      margin-top: 10px;
    }
    .actions button {
      background: none;
      border: none;
      color: white;
      cursor: pointer;
      font-size: 16px;
    }
    .actions button:hover {
      color: #1db954;
    }
  </style>
</head>
<body>
  <header>
    <h1>Redock</h1>
    <nav>
  
