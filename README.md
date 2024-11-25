<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Card</title>
  <link href="https://unpkg.com/lucide@latest/dist/umd/lucide.min.js" rel="stylesheet">
  <script src="https://unpkg.com/lucide@latest/dist/umd/lucide.min.js"></script>
  <script>
    lucide.createIcons();
  </script>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background-color: #fff;
      font-family: 'Noto Sans SC', sans-serif;
      margin: 0;
      padding: 0;
    }

   .card {
      max-width: 768px;
      border-radius: 0.75rem;
      box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
      background-color: #fff;
      color: #333;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

   .card-header {
      display: flex;
      align-items: center;
      padding: 1.5rem;
      border-bottom: 1px solid #e5e7eb;
    }

   .avatar {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      margin-right: 1.5rem;
      border: 3px solid linear-gradient(45deg, #FFC0CB, #87CEEB);
    }

   .header-info {
      display: flex;
      flex-direction: column;
    }

   .header-info h2 {
      font-size: 1.5rem;
      margin: 0;
    }

   .header-info p {
      margin: 0;
      font-size: 1rem;
      color: #666;
    }

   .card-section {
      padding: 1.5rem;
      border-bottom: 1px solid #e5e7eb;
    }

   .card-section h3 {
      display: flex;
      align-items: center;
      font-size: 1.25rem;
      margin: 0 0 1rem 0;
      color: #007bff;
    }

   .card-section h3 svg {
      margin-right: 0.5rem;
      width: 20px;
      height: 20px;
    }

   .recent-input {
      background-color: #f0f5ff;
      border-radius: 0.5rem;
      padding: 1rem;
    }

   .recent-input p {
      margin: 0;
      font-size: 1rem;
    }

   .highlight-list {
      list-style-type: none;
      margin: 0;
      padding: 0;
    }

   .highlight-list li {
      margin-bottom: 0.5rem;
      font-size: 1rem;
    }

   .expertise-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      grid-gap: 1rem;
    }

   .expertise-item {
      background-color: #e0f2fe;
      border-radius: 0.5rem;
      padding: 1rem;
      font-size: 1rem;
    }

   .hobby-icons {
      display: flex;
      align-items: center;
    }

   .hobby-icons svg {
      margin-right: 0.5rem;
      width: 20px;
      height: 20px;
      fill: #007bff;
    }

   .card-footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.5rem;
      background-color: #f8fafc;
    }

   .footer-attitude {
      font-size: 1rem;
    }

   .qr-code {
      width: 80px;
      height: 80px;
      background-color: #fff;
      border-radius: 0.25rem;
      display: flex;
      justify-content: center;
      align-items: center;
    }
  </style>
</head>

<body>
  <div class="card">
    <div class="card-header">
      <!-- Replace with your actual avatar URL -->
      <img src="https://via.placeholder.com/80" alt="Avatar" class="avatar">
      <div class="header-info">
        <h2>老旺</h2>
        <p>杭州余杭</p>
        <p>自由职业者, 私域营销专家, 知识IP变现顾问</p>
      </div>
    </div>
    <div class="card-section recent-input">
      <h3><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z"></path><path d="M11 7h2v7h-2z"></path></svg> 近期关键投入</h3>
      <p>打造知识服务产品0-1并探索内容获客玩法</p>
    </div>
    <div class="card-section">
      <h3><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z"></path><path d="M13 9h-2V7h2v2zm-2-4h2v2h-2V5z"></path></svg> 履历亮点</h3>
      <ul class="highlight-list">
        <li>拥有3年私域转化增长经验</li>
        <li>擅长私域营销体系搭建</li>
        <li>结合AI提效助力营销与转化</li>
      </ul>
    </div>
    <div class="card-section expertise-grid">
      <div class="expertise-item" style="background-color: #e0f2fe;">
        <h3><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z"></path><path d="M11 7h2v7h-2z"></path></svg> 私域营销</h3>
        <p>构建私域销售体系与前端承接转化链路</p>
      </div>
      <div class="expertise-item" style="background-color: #d1fae5;">
        <h3><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z"></path><path d="M13 9h-2V7h2v2zm-2-4h2v2h-2V5z"></path></svg> 数据链路优化</h3>
        <p>优化数据链路，搭建AI提效&SOP</p>
      </div>
      <div class="expertise-item" style="background-color: #e9d8fd;">
        <h3><svg xmlns="http://www.w3.org/2000/svg" viewBox="0
