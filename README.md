<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>간단 검색 엔진</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 150px;
      background-color: #f8f8f8;
    }
    input[type="text"] {
      width: 400px;
      padding: 10px;
      font-size: 18px;
      border: 1px solid #ccc;
      border-radius: 24px;
      outline: none;
      transition: box-shadow 0.3s ease;
    }
    input[type="text"]:focus {
      box-shadow: 0 0 5px #4285f4;
      border-color: #4285f4;
    }
    button {
      padding: 10px 20px;
      font-size: 18px;
      margin-left: 10px;
      border: none;
      background-color: #4285f4;
      color: white;
      border-radius: 24px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #357ae8;
    }
  </style>
</head>
<body>
  <h1>간단 검색 엔진</h1>
  <form id="searchForm" action="https://www.google.com/search" method="GET" target="_blank">
    <input type="text" name="q" placeholder="검색어를 입력하세요" required />
    <button type="submit">검색</button>
  </form>
</body>
</html>
