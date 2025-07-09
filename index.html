<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta http-equiv="X-Frame-Options" content="DENY">
    <meta http-equiv="Content-Security-Policy" content="frame-ancestors 'none';">
    <meta name="description" content="億家人居家長照機構 - 專業額度試算系統">
    <meta name="keywords" content="居家長照,額度試算,億家人,長期照護">
    <title>億家人©額度試算系統</title>
    
    <!-- Progressive Web App 支援 -->
    <link rel="manifest" href="data:application/json;base64,eyJuYW1lIjoi5Yi654aH6aGN5aCx6YOo6Kmm566X57O757WEIiwic2hvcnRfbmFtZSI6IumBoea9puipqeevlyIsInN0YXJ0X3VybCI6Ii8iLCJkaXNwbGF5Ijoic3RhbmRhbG9uZSIsImJhY2tncm91bmRfY29sb3IiOiIjZjVmNWY1IiwidGhlbWVfY29sb3IiOiIjNENBRjUwIn0=">
    <meta name="theme-color" content="#4CAF50">
    
    <!-- 預載入關鍵資源 -->
    <link rel="preload" href="https://cdn.glitch.global/6faa4221-c6cd-41f5-818e-402ed23ad722/Billion%20Family%20logo.png?v=1747023904594" as="image">
    
    <style>
        /* CSS 變數定義 - 提升可維護性 */
        :root {
            --primary-color: #4CAF50;
            --primary-dark: #45a049;
            --secondary-color: #2196F3;
            --danger-color: #f44336;
            --warning-color: #ff9800;
            --success-color: #4CAF50;
            --info-color: #2196F3;
            --light-bg: #f9f9f9;
            --border-color: #ddd;
            --text-primary: #333;
            --text-secondary: #666;
            --font-size-base: 14px;
            --border-radius: 4px;
            --spacing-sm: 5px;
            --spacing-md: 10px;
            --spacing-lg: 20px;
            --box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        /* 基礎重置與字體設定 */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: "Microsoft JhengHei", "Segoe UI", Arial, sans-serif;
            line-height: 1.6;
            background: var(--light-bg);
            color: var(--text-primary);
            font-size: var(--font-size-base);
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }

        /* 安全保護樣式 */
        .no-select {
            -webkit-user-select: none;
            -moz-user-select: none;
            -ms-user-select: none;
            user-select: none;
            -webkit-touch-callout: none;
        }
        
        input, textarea, select {
            -webkit-user-select: text;
            -moz-user-select: text;
            -ms-user-select: text;
            user-select: text;
        }
        
        img {
            -webkit-user-drag: none;
            -khtml-user-drag: none;
            -moz-user-drag: none;
            -o-user-drag: none;
            user-drag: none;
            pointer-events: none;
        }

        /* 浮水印系統 */
        .watermark-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 9999;
            overflow: hidden;
        }
        
        .watermark-text {
            position: absolute;
            color: rgba(0, 0, 0, 0.03);
            font-size: 20px;
            font-weight: bold;
            transform: rotate(-45deg);
            white-space: nowrap;
        }

        /* 安全提示 */
        .security-notice {
            position: fixed;
            bottom: var(--spacing-lg);
            right: var(--spacing-lg);
            background: rgba(0, 0, 0, 0.8);
            color: white;
            padding: var(--spacing-md) 15px;
            border-radius: var(--border-radius);
            font-size: 12px;
            display: none;
            z-index: 10000;
            animation: fadeInOut 3s ease-in-out;
        }
        
        @keyframes fadeInOut {
            0% { opacity: 0; }
            20% { opacity: 1; }
            80% { opacity: 1; }
            100% { opacity: 0; }
        }

        /* 列印保護 */
        @media print {
            body {
                display: none !important;
            }
            
            body::after {
                content: "© 2023-2025 億家人居家長照機構 - 此內容受版權保護，禁止列印";
                display: block !important;
                font-size: 24px;
                text-align: center;
                padding: 50px;
            }
        }

        /* 主容器 */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            padding: var(--spacing-lg);
            box-shadow: var(--box-shadow);
            position: relative;
            min-height: 100vh;
        }

        /* 載入動畫 */
        .loading {
            display: none;
            text-align: center;
            padding: var(--spacing-lg);
        }

        .spinner {
            border: 3px solid var(--light-bg);
            border-top: 3px solid var(--primary-color);
            border-radius: 50%;
            width: 30px;
            height: 30px;
            animation: spin 1s linear infinite;
            margin: 0 auto var(--spacing-md);
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* 響應式設計 */
        @media screen and (max-width: 1200px) {
            .container {
                width: 100%;
                min-width: auto;
                padding: var(--spacing-md);
            }
            
            .config-section {
                flex-direction: column;
            }
            
            .config-item {
                width: 100% !important;
                margin-bottom: 15px;
            }
        }

        @media screen and (max-width: 768px) {
            :root {
                --font-size-base: 13px;
            }

            .title-container {
                flex-wrap: nowrap;
                padding-bottom: 15px;
            }
            
            .title-left,
            .title-right {
                width: 25%;
            }
            
            .title-center {
                width: 50%;
            }
            
            .logo-img {
                height: 40px;
                object-fit: contain;
            }

            #serviceTable {
                font-size: 12px;
            }
            
            #serviceTable th,
            #serviceTable td {
                padding: 4px 2px;
            }

            /* 固定欄位設定 */
            #serviceTable th:nth-child(1),
            #serviceTable td:nth-child(1) {
                position: sticky;
                left: 0;
                background-color: var(--light-bg);
                z-index: 10;
                border-right: 2px solid var(--border-color);
                min-width: 80px;
                max-width: 100px;
            }
            
            #serviceTable th:nth-child(2),
            #serviceTable td:nth-child(2) {
                position: sticky;
                left: 80px;
                background-color: var(--light-bg);
                z-index: 10;
                border-right: 2px solid var(--border-color);
                min-width: 60px;
                max-width: 80px;
            }
        }

        /* 標題區域 */
        .title-container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: var(--spacing-lg);
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: var(--spacing-md);
            position: relative;
        }
        
        .title-left,
        .title-right {
            width: 30%;
            display: flex;
            align-items: center;
        }
        
        .title-center {
            width: 40%;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .title-right {
            justify-content: flex-end;
        }
        
        .logo-img {
            height: 60px;
            object-fit: contain;
        }
        
        h1 {
            color: var(--text-primary);
            margin: 0;
            font-size: 1.8rem;
        }

        /* 按鈕系統 */
        .btn {
            padding: var(--spacing-md) var(--spacing-lg);
            cursor: pointer;
            border: none;
            border-radius: var(--border-radius);
            font-weight: bold;
            text-decoration: none;
            display: inline-block;
            text-align: center;
            transition: all 0.3s ease;
            font-family: inherit;
            font-size: var(--font-size-base);
        }

        .btn-primary {
            background-color: var(--primary-color);
            color: white;
        }

        .btn-primary:hover {
            background-color: var(--primary-dark);
            transform: translateY(-1px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        .btn-secondary {
            background-color: var(--secondary-color);
            color: white;
        }

        .btn-danger {
            background-color: var(--danger-color);
            color: white;
        }

        .btn-small {
            padding: var(--spacing-sm) var(--spacing-md);
            font-size: 12px;
        }

        .btn:disabled {
            background-color: #cccccc;
            cursor: not-allowed;
            opacity: 0.6;
        }

        #clearBtn {
            width: 80px;
        }

        /* 配置區域 */
        .config-section {
            display: flex;
            flex-wrap: wrap;
            gap: var(--spacing-lg);
            margin-bottom: var(--spacing-lg);
        }
        
        .config-item {
            flex: 1;
            min-width: 200px;
            border: 1px solid var(--border-color);
            padding: var(--spacing-md);
            background-color: var(--light-bg);
            border-radius: var(--border-radius);
        }

        .block-title {
            text-align: center;
            font-weight: bold;
            margin-bottom: var(--spacing-sm);
            padding: var(--spacing-sm) 0;
            color: var(--text-primary);
            border-bottom: 1px solid var(--border-color);
            font-size: 1.1rem;
        }

        /* 輸入群組 */
        .input-group {
            margin: var(--spacing-sm) 0;
            display: flex;
            align-items: center;
            min-height: 36px;
        }
        
        .input-group label {
            width: 100px;
            display: inline-block;
            white-space: nowrap;
            font-weight: 500;
        }
        
        .input-group input,
        .input-group select,
        .input-group span {
            flex: 1;
            min-height: 20px;
        }

        /* 表單控制項 */
        input[type="number"],
        input[type="text"],
        select {
            padding: var(--spacing-sm);
            border: 1px solid var(--border-color);
            border-radius: var(--border-radius);
            font-family: inherit;
            font-size: var(--font-size-base);
            transition: border-color 0.3s ease;
        }

        input[type="number"]:focus,
        input[type="text"]:focus,
        select:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 2px rgba(76, 175, 80, 0.2);
        }

        input[type="number"] {
            text-align: right;
            width: 80px;
        }

        input[type="number"]::-webkit-inner-spin-button,
        input[type="number"]::-webkit-outer-spin-button {
            -webkit-appearance: none;
            margin: 0;
        }

        input[type="number"] {
            -moz-appearance: textfield;
        }

        /* 單選按鈕組 */
        .radio-group,
        .cms-radio-group {
            display: flex;
            flex-wrap: wrap;
            gap: 2px;
            width: 100%;
            justify-content: flex-end;
            margin-left: auto;
        }
        
        .radio-button,
        .cms-radio-button {
            display: inline-block;
        }
        
        .radio-button input[type="radio"],
        .cms-radio-button input[type="radio"] {
            display: none;
        }
        
        .radio-button label,
        .cms-radio-button label {
            display: inline-block;
            padding: 3px 6px;
            cursor: pointer;
            border: 1px solid var(--border-color);
            border-radius: var(--border-radius);
            background-color: var(--light-bg);
            text-align: center;
            font-size: var(--font-size-base);
            min-width: 16px;
            transition: all 0.3s ease;
        }
        
        .radio-button input[type="radio"]:checked + label,
        .cms-radio-button input[type="radio"]:checked + label {
            background-color: var(--primary-color);
            color: white;
            border-color: var(--primary-color);
            transform: scale(1.05);
        }

        /* 表格樣式 */
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 0;
            font-size: var(--font-size-base);
        }
        
        th,
        td {
            border: 1px solid var(--border-color);
            padding: 8px;
            text-align: center;
        }
        
        th {
            background-color: var(--light-bg);
            font-weight: bold;
            position: sticky;
            top: 0;
            z-index: 5;
        }

        /* 加成次數表格 */
        .bonus-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: var(--spacing-md);
        }
        
        .bonus-table th,
        .bonus-table td {
            border: 1px solid var(--border-color);
            padding: 6px;
            text-align: center;
            font-size: var(--font-size-base);
        }
        
        .bonus-table th {
            background-color: #f2f2f2;
        }

        /* 服務項目表格 */
        #serviceTable {
            display: block;
            overflow-x: auto;
            white-space: nowrap;
            max-height: 70vh;
            overflow-y: auto;
        }

        /* 工具類別 */
        .text-right { text-align: right; }
        .text-left { text-align: left; }
        .text-center { text-align: center; }
        .bold-text { font-weight: bold; }
        .red-text { color: var(--danger-color); }
        .blue-text { color: var(--secondary-color); }
        .green-text { color: var(--success-color); }

        .no-border {
            background-color: transparent !important;
            border: none !important;
            padding: var(--spacing-sm);
            border-radius: 0;
        }

        .hide-column { display: none; }
        .proposed-bg { background-color: #e8f5e9; }
        .self-pay-bg { background-color: #e3f2fd; }

        /* 機構資訊 */
        .org-info-container {
            display: flex;
            align-items: center;
            justify-content: flex-start;
            margin: var(--spacing-lg) 0;
            padding: 15px;
            border: 1px solid var(--border-color);
            border-radius: 8px;
            background-color: var(--light-bg);
        }
        
        .org-info {
            color: var(--text-secondary);
            font-size: var(--font-size-base);
            line-height: 1.4;
            white-space: pre-line;
            flex: 1;
            text-align: left;
        }
        
        .qrcode-img {
            height: 120px;
            width: 120px;
            object-fit: contain;
            margin-right: 15px;
        }

        /* 警告訊息 */
        .warning-container {
            display: none;
        }

        #overBudgetWarning {
            background-color: #ffdddd;
            color: var(--danger-color);
            padding: var(--spacing-md);
            text-align: center;
            margin: var(--spacing-md) 0;
            font-weight: bold;
            border: 1px solid var(--danger-color);
            border-radius: var(--border-radius);
            display: none;
        }

        /* 頁尾 */
        .footer {
            margin-top: 30px;
            padding-top: 15px;
            border-top: 1px solid var(--border-color);
            text-align: center;
            color: var(--text-secondary);
            font-size: var(--font-size-base);
        }
        
        .footer a {
            color: var(--text-primary);
            font-weight: bold;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer a:hover {
            text-decoration: underline;
            color: var(--primary-color);
        }

        /* 標誌鏈接 */
        .logo-link {
            display: flex;
            align-items: center;
            text-decoration: none;
            transition: opacity 0.3s ease;
        }
        
        .logo-link:hover {
            opacity: 0.9;
        }

        /* 響應式機構資訊 */
        .org-info-desktop {
            display: block;
        }
        
        .org-info-mobile {
            display: none;
        }
        
        @media screen and (max-width: 768px) {
            .org-info-desktop {
                display: none;
            }
            
            .org-info-mobile {
                display: block;
            }

            .qrcode-img {
                width: 100px;
                height: 100px;
                margin-right: 15px;
            }
        }

        /* 進度指示器 */
        .progress-container {
            margin: var(--spacing-md) 0;
            display: none;
        }

        .progress-bar {
            width: 100%;
            height: 4px;
            background-color: var(--light-bg);
            border-radius: 2px;
            overflow: hidden;
        }

        .progress-fill {
            height: 100%;
            background-color: var(--primary-color);
            width: 0%;
            transition: width 0.3s ease;
        }

        /* 提示訊息 */
        .toast {
            position: fixed;
            top: var(--spacing-lg);
            right: var(--spacing-lg);
            background: var(--primary-color);
            color: white;
            padding: var(--spacing-md) var(--spacing-lg);
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            z-index: 10001;
            transform: translateX(400px);
            transition: transform 0.3s ease;
        }

        .toast.show {
            transform: translateX(0);
        }

        .toast.error {
            background: var(--danger-color);
        }

        .toast.warning {
            background: var(--warning-color);
        }

        .toast.success {
            background: var(--success-color);
        }

        /* 可存取性改善 */
        @media (prefers-reduced-motion: reduce) {
            *,
            *::before,
            *::after {
                animation-duration: 0.01ms !important;
                animation-iteration-count: 1 !important;
                transition-duration: 0.01ms !important;
            }
        }

        /* 高對比模式支援 */
        @media (prefers-contrast: high) {
            :root {
                --border-color: #000;
                --text-primary: #000;
                --light-bg: #fff;
            }
        }

        /* 深色模式支援 */
        @media (prefers-color-scheme: dark) {
            :root {
                --light-bg: #2d2d2d;
                --text-primary: #ffffff;
                --text-secondary: #cccccc;
                --border-color: #555;
            }

            .container {
                background: #1a1a1a;
            }

            th {
                background-color: #333;
            }
        }
    </style>
</head>
<body class="no-select">
    <!-- 浮水印容器 -->
    <div class="watermark-container" id="watermarkContainer"></div>
    
    <!-- 安全提示 -->
    <div class="security-notice" id="securityNotice">
        ⚠️ 內容受版權保護
    </div>

    <!-- 載入動畫 -->
    <div class="loading" id="loadingIndicator">
        <div class="spinner"></div>
        <p>系統載入中...</p>
    </div>

    <!-- 進度指示器 -->
    <div class="progress-container" id="progressContainer">
        <div class="progress-bar">
            <div class="progress-fill" id="progressFill"></div>
        </div>
    </div>
    
    <div class="container">
        <!-- 標題區域 -->
        <div class="title-container">
            <div class="title-left">
                <a href="https://cdn.glitch.global/6faa4221-c6cd-41f5-818e-402ed23ad722/Billion%20Family%20.png?v=1748412124517" class="logo-link" target="_blank" rel="noopener">
                    <img src="https://cdn.glitch.global/6faa4221-c6cd-41f5-818e-402ed23ad722/Billion%20Family%20logo.png?v=1747023904594" alt="億家人居家長照機構標誌" class="logo-img" loading="lazy">
                </a>
            </div>
            <div class="title-center">
                <h1>額度試算系統</h1>
            </div>
            <div class="title-right">
                <button id="clearBtn" class="btn btn-primary btn-small" aria-label="重置所有資料">重置</button>
            </div>
        </div>
        
        <!-- 基本數據配置區域 -->
        <div class="config-section">
            <div class="config-item">
                <h3 class="block-title">居服薪資(6/4)</h3>
                <div class="input-group">
                    <label for="monthlyAmount">預計月薪資：</label>
                    <span id="monthlyAmount" class="no-border text-right" aria-live="polite"></span>
                </div>
                <div class="horizontal-divider"></div>
                <div class="title-row">
                    <div class="bonus-count-title">加成次數</div>
                    <div>
                        <button id="saveRateBtn" class="btn btn-secondary btn-small">儲存</button>
                        <button id="editRateBtn" class="btn btn-danger btn-small" style="display: none;">編輯</button>
                    </div>
                </div>
                <table class="bonus-table">
                    <thead>
                        <tr>
                            <th>項目</th>
                            <th>價格</th>
                            <th>次數</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td class="item-code">AA05</td>
                            <td><input type="text" id="rate_price_AA05" class="price-input" aria-label="AA05價格"></td>
                            <td><input type="number" id="rate_count_AA05" min="0" class="text-right" aria-label="AA05次數"></td>
                        </tr>
                        <tr>
                            <td class="item-code">AA06</td>
                            <td><input type="text" id="rate_price_AA06" class="price-input" aria-label="AA06價格"></td>
                            <td><input type="number" id="rate_count_AA06" min="0" class="text-right" aria-label="AA06次數"></td>
                        </tr>
                        <tr>
                            <td class="item-code">AA08</td>
                            <td><input type="text" id="rate_price_AA08" class="price-input" aria-label="AA08價格"></td>
                            <td><input type="number" id="rate_count_AA08" min="0" class="text-right" aria-label="AA08次數"></td>
                        </tr>
                        <tr>
                            <td class="item-code">AA09</td>
                            <td><input type="text" id="rate_price_AA09" class="price-input" aria-label="AA09價格"></td>
                            <td><input type="number" id="rate_count_AA09" min="0" class="text-right" aria-label="AA09次數"></td>
                        </tr>
                        <tr>
                            <td class="item-code">AA11</td>
                            <td><input type="text" id="rate_price_AA11" class="price-input" aria-label="AA11價格"></td>
                            <td><input type="number" id="rate_count_AA11" min="0" class="text-right" aria-label="AA11次數"></td>
                        </tr>
                    </tbody>
                </table>
            </div>
            
            <div class="config-item">
                <h3 class="block-title">基本資料</h3>
                <div class="input-group">
                    <label>身分別：</label>
                    <div class="radio-group" role="radiogroup" aria-label="身分別選擇">
                        <div class="radio-button">
                            <input type="radio" id="identity1" name="identityType" value="一般戶" checked>
                            <label for="identity1">一般戶</label>
                        </div>
                        <div class="radio-button">
                            <input type="radio" id="identity2" name="identityType" value="中低收">
                            <label for="identity2">中低收</label>
                        </div>
                        <div class="radio-button">
                            <input type="radio" id="identity3" name="identityType" value="低收">
                            <label for="identity3">低收</label>
                        </div>
                    </div>
                </div>
                <div class="input-group">
                    <label>CMS等級：</label>
                    <div class="cms-radio-group" role="radiogroup" aria-label="CMS等級選擇">
                        <div class="radio-button cms-radio-button">
                            <input type="radio" id="cms2" name="cmsLevel" value="2">
                            <label for="cms2">2</label>
                        </div>
                        <div class="radio-button cms-radio-button">
                            <input type="radio" id="cms3" name="cmsLevel" value="3">
                            <label for="cms3">3</label>
                        </div>
                        <div class="radio-button cms-radio-button">
                            <input type="radio" id="cms4" name="cmsLevel" value="4">
                            <label for="cms4">4</label>
                        </div>
                        <div class="radio-button cms-radio-button">
                            <input type="radio" id="cms5" name="cmsLevel" value="5">
                            <label for="cms5">5</label>
                        </div>
                        <div class="radio-button cms-radio-button">
                            <input type="radio" id="cms6" name="cmsLevel" value="6">
                            <label for="cms6">6</label>
                        </div>
                        <div class="radio-button cms-radio-button">
                            <input type="radio" id="cms7" name="cmsLevel" value="7">
                            <label for="cms7">7</label>
                        </div>
                        <div class="radio-button cms-radio-button">
                            <input type="radio" id="cms8" name="cmsLevel" value="8">
                            <label for="cms8">8</label>
                        </div>
                    </div>
                </div>
                <div class="input-group">
                    <label for="usageQuota">留用額度：</label>
                    <input type="text" id="usageQuota" value="" class="text-right" aria-label="留用額度">
                </div>
                <div class="input-group">
                    <label>給付額度：</label>
                    <span id="paymentQuota" class="no-border text-right" aria-live="polite"></span>
                </div>
            </div>
            
            <div class="config-item">
                <h3 class="block-title">個案額度及自付額</h3>
                <div class="input-group">
                    <label>額度總計：</label>
                    <span id="quotaTotal" class="no-border text-right" aria-live="polite"></span>
                </div>
                <div class="input-group">
                    <label>剩餘額度：</label>
                    <span id="remainingQuota" class="no-border text-right" aria-live="polite"></span>
                </div>
                <div class="warning-container">
                    <div id="overBudgetWarning" role="alert">
                        已超額！部分負擔需加自費！<br>
                        請點選「超額分配」
                    </div>
                    <button id="excessAllocationBtn" class="btn btn-danger">超額分配</button>
                </div>
                <div class="input-group partial-burden-row">
                    <label>部分負擔：</label>
                    <span id="partialBurden" class="no-border text-right" aria-live="polite"></span>
                </div>
                <div class="input-group self-pay-row">
                    <label>自費：</label>
                    <span id="selfPay" class="no-border text-right red-text" aria-live="polite"></span>
                </div>
                <div class="input-group total-pay-row">
                    <label>自付總計：</label>
                    <span id="totalPay" class="no-border text-right bold-text" aria-live="polite"></span>
                </div>
                <button id="updateBtn" class="btn btn-secondary" style="display: none;">更新</button>
            </div>
        </div>
        
        <!-- 機構資訊容器 -->
        <div class="org-info-container">
            <img src="https://cdn.glitch.global/6faa4221-c6cd-41f5-818e-402ed23ad722/messageImage_1748412882275.jpg?v=17484129229534" alt="億家人居家長照機構QR Code" class="qrcode-img" loading="lazy">
            <!-- 桌面版格式 -->
            <div class="org-info org-info-desktop">我們是億家人居家長照機構
負責區域為新莊、板橋、樹林、五股
歡迎轉案!
聯絡電話:02-2276-0087
<div style="color:LightSalmon">
<b>在億家人，大家都是一家人</b>
</div></div>
            <!-- 手機版格式 -->
            <div class="org-info org-info-mobile">我們是億家人居家長照機構，
負責區域為新莊、板橋、
樹林、五股，歡迎轉案!
聯絡電話:02-2276-0087
<div style="color:LightSalmon">
<b>在億家人，大家都是一家人</b>
</div></div>
        </div>
        
        <!-- 服務項目表格 -->
        <table id="serviceTable" role="table" aria-label="服務項目表格">
            <thead>
                <tr>
                    <th scope="col">服務項目</th>
                    <th scope="col"><div>給付</div><div>價格</div></th>
                    <th scope="col">周次數</th>
                    <th scope="col">月次數</th>
                    <th scope="col">總次數</th>
                    <th scope="col">使用額度</th>
                    <th scope="col" class="basic-burden-col">基本負擔</th>
                    <th scope="col" class="proposed-count-col">提出次數</th>
                    <th scope="col" class="proposed-amount-col">提出額度</th>
                    <th scope="col" class="burden-amount-col">負擔</th>
                    <th scope="col" class="self-count-col">自費次數</th>
                    <th scope="col" class="self-amount-col">自費額度</th>
                </tr>
            </thead>
            <tbody id="serviceTableBody">
                <!-- 動態生成內容 -->
            </tbody>
        </table>
        
        <!-- 頁尾版權資訊 -->
        <div class="footer">
            <a href="https://cdn.glitch.global/6faa4221-c6cd-41f5-818e-402ed23ad722/Billion%20Family%20.png?v=1748412124517" target="_blank" rel="noopener">億家人居家長照機構</a> © 2023-2025
        </div>
    </div>

    <script>
        // 應用程式主要類別
        class QuotaCalculator {
            constructor() {
                this.serviceItems = [
                    { code: 'BA01', name: '基本身體清潔', price: 260 },
                    { code: 'BA02', name: '基本日常照顧', price: 195 },
                    { code: 'BA03', name: '測量生命徵象', price: 35 },
                    { code: 'BA04', name: '協助進食或管灌', price: 130 },
                    { code: 'BA05', name: '餐食照顧', price: 310 },
                    { code: 'BA07', name: '協助沐浴及洗頭', price: 325 },
                    { code: 'BA08', name: '足部照護', price: 500 },
                    { code: 'BA10', name: '翻身拍背', price: 155 },
                    { code: 'BA11', name: '肢體關節活動', price: 195 },
                    { code: 'BA12', name: '協助上下樓梯', price: 130 },
                    { code: 'BA13', name: '陪同外出', price: 195 },
                    { code: 'BA14', name: '陪同就醫', price: 685 },
                    { code: 'BA15', name: '家務協助', price: 195 },
                    { code: 'BA16', name: '代購', price: 130 },
                    { code: 'BA17a', name: '人工氣道管抽吸', price: 75 },
                    { code: 'BA17b', name: '口腔內抽吸', price: 65 },
                    { code: 'BA17c', name: '管路清潔', price: 50 },
                    { code: 'BA17d', name: '通便、驗血糖', price: 50 },
                    { code: 'BA17e', name: '依指示置入藥盒', price: 50 },
                    { code: 'BA18', name: '安全看視', price: 200 },
                    { code: 'BA20', name: '陪伴服務', price: 175 },
                    { code: 'BA23', name: '協助洗頭', price: 200 },
                    { code: 'BA24', name: '協助排泄', price: 220 },
                    { code: 'GA09', name: '喘息2小時/支', price: 770 },
                    { code: 'SC09', name: '短照2小時/支', price: 770 }
                ];

                this.cmsPaymentMap = {
                    "2": 10020, "3": 15460, "4": 18580, "5": 24100,
                    "6": 28070, "7": 32090, "8": 36180
                };

                this.identityRateMap = {
                    "一般戶": 0.16, "中低收": 0.05, "低收": 0
                };

                this.state = {
                    hasPerformedExcessAllocation: false,
                    originalValues: {},
                    isRateEditMode: true,
                    isEditMode: false,
                    tableHasChanged: false
                };

                this.init();
            }

            // 初始化應用程式
            init() {
                this.setupSecurity();
                this.setupEventListeners();
                this.initializeServiceList();
                this.loadPricesFromStorage();
                this.updateRatesAndQuotas();
                this.recalculateTotals();
                this.updateTableColumnsVisibility();
                this.hideLoading();
                this.showToast('系統載入完成', 'success');
            }

            // 設定安全保護
            setupSecurity() {
                this.createWatermarks();
                this.setupSecurityEvents();
            }

            // 建立浮水印
            createWatermarks() {
                const container = document.getElementById('watermarkContainer');
                const text = '億家人居家長照機構 © 版權所有';
                
                for (let i = 0; i < 20; i++) {
                    const watermark = document.createElement('div');
                    watermark.className = 'watermark-text';
                    watermark.textContent = text;
                    watermark.style.top = `${(i % 5) * 200 + 50}px`;
                    watermark.style.left = `${Math.floor(i / 5) * 300 - 100}px`;
                    container.appendChild(watermark);
                }
            }

            // 設定安全事件
            setupSecurityEvents() {
                // 禁用右鍵選單
                document.addEventListener('contextmenu', (e) => {
                    e.preventDefault();
                    this.showSecurityNotice();
                    return false;
                });

                // 禁用特定鍵盤快捷鍵
                document.addEventListener('keydown', (e) => {
                    if (e.keyCode === 123 || // F12
                        (e.ctrlKey && e.shiftKey && [73, 74, 67].includes(e.keyCode)) || // Ctrl+Shift+I/J/C
                        (e.ctrlKey && e.keyCode === 83) || // Ctrl+S
                        (e.ctrlKey && e.keyCode === 85)) { // Ctrl+U
                        e.preventDefault();
                        this.showSecurityNotice();
                        return false;
                    }
                });

                // 禁用列印
                window.addEventListener('beforeprint', (e) => {
                    alert('此頁面受版權保護，禁止列印。\n如需列印功能，請聯繫系統管理員。');
                    e.preventDefault();
                    return false;
                });
            }

            // 顯示安全提示
            showSecurityNotice() {
                const notice = document.getElementById('securityNotice');
                notice.style.display = 'block';
                setTimeout(() => {
                    notice.style.display = 'none';
                }, 3000);
            }

            // 設定事件監聽器
            setupEventListeners() {
                // 按鈕事件
                document.getElementById('excessAllocationBtn').addEventListener('click', () => this.runOptimization());
                document.getElementById('clearBtn').addEventListener('click', () => this.clearData());
                document.getElementById('updateBtn').addEventListener('click', () => this.clearOptimizationResults());
                document.getElementById('saveRateBtn').addEventListener('click', () => this.saveRateSettings());
                document.getElementById('editRateBtn').addEventListener('click', () => this.editRateSettings());

                // 表單事件
                document.querySelectorAll('input[name="identityType"]').forEach(radio => {
                    radio.addEventListener('change', () => this.updateRatesAndQuotas());
                });

                document.querySelectorAll('input[name="cmsLevel"]').forEach(radio => {
                    radio.addEventListener('change', () => this.updateRatesAndQuotas());
                });

                document.getElementById('usageQuota').addEventListener('input', (e) => {
                    this.formatNumberInput(e);
                    if (!this.state.isEditMode) {
                        this.recalculateTotals();
                        this.checkBudget();
                    }
                });

                // 響應式設計事件
                window.addEventListener('resize', () => this.adjustResponsiveLayout());
            }

            // 格式化數字輸入
            formatNumberInput(e) {
                const value = e.target.value.replace(/,/g, '');
                if (!isNaN(value)) {
                    e.target.value = value === '0' ? '' : this.formatNumber(parseInt(value) || 0);
                }
            }

            // 初始化服務項目列表
            initializeServiceList() {
                const tbody = document.getElementById('serviceTableBody');
                tbody.innerHTML = '';
                
                this.serviceItems.forEach((item, index) => {
                    const row = this.createServiceRow(item, index);
                    tbody.appendChild(row);
                });
            }

            // 建立服務項目行
            createServiceRow(item, index) {
                const row = document.createElement('tr');
                row.setAttribute('data-code', item.code);
                row.setAttribute('data-index', index);
                row.innerHTML = `
                    <td class="text-left"><div>${item.code}</div><div>${item.name}</div></td>
                    <td class="text-right">${this.formatNumber(item.price)}</td>
                    <td><input type="number" class="weekly-count" min="0" value="" aria-label="${item.name} 周次數"></td>
                    <td class="monthly-count text-right"></td>
                    <td><input type="number" class="total-count" min="0" value="" aria-label="${item.name} 總次數"></td>
                    <td class="usage-amount text-right"></td>
                    <td class="basic-burden text-right basic-burden-col"></td>
                    <td class="proposed-count text-right proposed-bg proposed-count-col"></td>
                    <td class="proposed-amount text-right proposed-bg proposed-amount-col"></td>
                    <td class="burden-amount text-right proposed-bg burden-amount-col"></td>
                    <td class="self-count text-right self-pay-bg self-count-col"></td>
                    <td class="self-amount text-right self-pay-bg self-amount-col"></td>
                `;

                this.setupRowEventListeners(row);
                return row;
            }

            // 設定行的事件監聽器
            setupRowEventListeners(row) {
                const weeklyCountInput = row.querySelector('.weekly-count');
                const totalCountInput = row.querySelector('.total-count');

                weeklyCountInput.addEventListener('input', () => {
                    if (this.state.isEditMode) return;
                    
                    if (weeklyCountInput.value === '0') weeklyCountInput.value = '';
                    const weeklyCount = parseInt(weeklyCountInput.value) || 0;
                    const monthlyCount = Math.ceil(weeklyCount * 4.5);
                    row.querySelector('.monthly-count').textContent = monthlyCount === 0 ? '' : monthlyCount;
                    
                    this.recalculateRow(row);
                    this.recalculateTotals();
                    this.checkBudget();
                    this.checkForChanges();
                });

                totalCountInput.addEventListener('input', () => {
                    if (this.state.isEditMode) return;
                    
                    if (totalCountInput.value === '0') totalCountInput.value = '';
                    this.recalculateRow(row);
                    this.recalculateTotals();
                    this.checkBudget();
                    this.checkForChanges();
                });
            }

            // 檢查是否有變更
            checkForChanges() {
                if (this.state.hasPerformedExcessAllocation) {
                    this.state.tableHasChanged = true;
                    this.checkUpdateButtonDisplay();
                }
            }

            // 從儲存空間載入價格
            loadPricesFromStorage() {
                const bonusItems = ['AA05', 'AA06', 'AA08', 'AA09', 'AA11'];
                bonusItems.forEach(code => {
                    const priceCookie = this.getCookie(`rate_price_${code}`);
                    if (priceCookie) {
                        const element = document.getElementById(`rate_price_${code}`);
                        if (element) {
                            element.value = this.formatNumber(parseInt(priceCookie));
                        }
                    }
                });
            }

            // Cookie 操作
            setCookie(name, value, days = 365) {
                const date = new Date();
                date.setTime(date.getTime() + (days * 24 * 60 * 60 * 1000));
                const expires = "expires=" + date.toUTCString();
                document.cookie = `${name}=${value};${expires};path=/;SameSite=Strict`;
            }

            getCookie(name) {
                const cname = name + "=";
                const decodedCookie = decodeURIComponent(document.cookie);
                const ca = decodedCookie.split(';');
                
                for(let i = 0; i < ca.length; i++) {
                    let c = ca[i];
                    while (c.charAt(0) === ' ') {
                        c = c.substring(1);
                    }
                    if (c.indexOf(cname) === 0) {
                        return c.substring(cname.length, c.length);
                    }
                }
                return "";
            }

            // 格式化數字顯示
            formatNumber(number) {
                return number.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            }

            // 重新計算行數據
            recalculateRow(row) {
                const priceElement = row.querySelector('td:nth-child(2)');
                const price = parseInt(priceElement.textContent.replace(/,/g, '')) || 0;
                const monthlyCount = parseInt(row.querySelector('.monthly-count').textContent) || 0;
                const totalCount = parseInt(row.querySelector('.total-count').value) || 0;
                const usageAmount = (monthlyCount + totalCount) * price;

                row.querySelector('.usage-amount').textContent = usageAmount === 0 ? '' : this.formatNumber(usageAmount);

                // 計算基本負擔
                const identityType = document.querySelector('input[name="identityType"]:checked')?.value || "一般戶";
                const percentRate = this.identityRateMap[identityType] || 0;
                const unitBurden = Math.floor(price * percentRate);
                const basicBurden = (monthlyCount + totalCount) * unitBurden;

                row.querySelector('.basic-burden').textContent = basicBurden === 0 ? '' : this.formatNumber(basicBurden);
            }

            // 重新計算總計
            recalculateTotals() {
                if (this.state.isEditMode) return;

                let totalUsage1to23 = 0;
                let totalUsage24to25 = 0;
                let totalBurden = 0;
                let totalSelfAmount = 0;
                let totalProposedAmount = 0;
                let totalBurdenAmount = 0;

                document.querySelectorAll('#serviceTableBody tr').forEach(row => {
                    const index = parseInt(row.getAttribute('data-index'));
                    const usageAmount = parseInt(row.querySelector('.usage-amount').textContent.replace(/,/g, '')) || 0;
                    const basicBurden = parseInt(row.querySelector('.basic-burden').textContent.replace(/,/g, '')) || 0;

                    // 累加各項數據
                    const selfAmountCell = row.querySelector('.self-amount');
                    if (selfAmountCell?.textContent) {
                        totalSelfAmount += parseInt(selfAmountCell.textContent.replace(/,/g, '')) || 0;
                    }

                    const proposedAmountCell = row.querySelector('.proposed-amount');
                    if (proposedAmountCell?.textContent) {
                        totalProposedAmount += parseInt(proposedAmountCell.textContent.replace(/,/g, '')) || 0;
                    }

                    const burdenAmountCell = row.querySelector('.burden-amount');
                    if (burdenAmountCell?.textContent) {
                        totalBurdenAmount += parseInt(burdenAmountCell.textContent.replace(/,/g, '')) || 0;
                    }

                    if (index < 23) {
                        totalUsage1to23 += usageAmount;
                    } else {
                        totalUsage24to25 += usageAmount;
                    }
                    totalBurden += basicBurden;
                });

                this.updateDisplayValues(totalUsage1to23, totalUsage24to25, totalBurden, totalSelfAmount, totalProposedAmount, totalBurdenAmount);
                this.updateTableColumnsVisibility();
                this.checkUpdateButtonDisplay();
            }

            // 更新顯示值
            updateDisplayValues(totalUsage1to23, totalUsage24to25, totalBurden, totalSelfAmount, totalProposedAmount, totalBurdenAmount) {
                const quotaTotal = totalUsage1to23;
                
                // 更新月薪資
                this.updateMonthlyAmount(quotaTotal, totalUsage24to25);

                // 更新額度相關數據
                const usageQuota = parseInt(document.getElementById('usageQuota').value.replace(/,/g, '')) || 0;
                const paymentQuota = parseInt(document.getElementById('paymentQuota').textContent.replace(/,/g, '')) || 0;
                
                let remainingQuota;
                if (totalProposedAmount > 0) {
                    let totalProposedAmount1to23 = 0;
                    document.querySelectorAll('#serviceTableBody tr').forEach(row => {
                        const index = parseInt(row.getAttribute('data-index'));
                        if (index < 23) {
                            const proposedAmountCell = row.querySelector('.proposed-amount');
                            if (proposedAmountCell?.textContent) {
                                totalProposedAmount1to23 += parseInt(proposedAmountCell.textContent.replace(/,/g, '')) || 0;
                            }
                        }
                    });
                    remainingQuota = usageQuota + paymentQuota - totalProposedAmount1to23;
                } else {
                    remainingQuota = usageQuota + paymentQuota - quotaTotal;
                }

                // 更新顯示
                document.getElementById('quotaTotal').textContent = quotaTotal === 0 ? '' : this.formatNumber(quotaTotal);
                document.getElementById('remainingQuota').textContent = remainingQuota === 0 ? '' : this.formatNumber(remainingQuota);

                // 更新負擔相關顯示
                this.updateBurdenDisplay(totalBurden, totalBurdenAmount, totalSelfAmount, usageQuota, paymentQuota, quotaTotal, totalProposedAmount);
            }

            // 更新月薪資
            updateMonthlyAmount(quotaTotal, totalUsage24to25) {
                const monthlyAmountField = document.getElementById('monthlyAmount');
                
                if (this.state.isRateEditMode) {
                    monthlyAmountField.textContent = "請儲存加成次數";
                    monthlyAmountField.classList.add('red-text');
                } else {
                    monthlyAmountField.classList.remove('red-text');
                    let totalBonusAmount = 0;
                    
                    document.querySelectorAll('.bonus-table tbody tr').forEach(row => {
                        const price = parseInt(row.cells[1].textContent.replace(/,/g, '')) || 0;
                        const count = parseInt(row.cells[2].textContent) || 0;
                        totalBonusAmount += price * count;
                    });
                    
                    const monthlyAmount = (quotaTotal + totalUsage24to25) * 0.6 + totalBonusAmount;
                    monthlyAmountField.textContent = monthlyAmount === 0 ? '' : this.formatNumber(Math.round(monthlyAmount));
                }
            }

            // 更新負擔顯示
            updateBurdenDisplay(totalBurden, totalBurdenAmount, totalSelfAmount, usageQuota, paymentQuota, quotaTotal, totalProposedAmount) {
                const partialBurdenRow = document.querySelector('.partial-burden-row');
                const totalPayRow = document.querySelector('.total-pay-row');
                const selfPayRow = document.querySelector('.self-pay-row');
                const totalAvailable = usageQuota + paymentQuota;

                if (quotaTotal > totalAvailable && totalProposedAmount === 0) {
                    partialBurdenRow.style.display = 'none';
                    totalPayRow.style.display = 'none';
                } else {
                    partialBurdenRow.style.display = 'flex';
                    totalPayRow.style.display = (usageQuota + paymentQuota - quotaTotal) < 0 ? 'none' : 'flex';
                    
                    const displayBurden = totalBurdenAmount > 0 ? totalBurdenAmount : totalBurden;
                    document.getElementById('partialBurden').textContent = displayBurden === 0 ? '' : this.formatNumber(displayBurden);
                }

                document.getElementById('selfPay').textContent = totalSelfAmount === 0 ? '' : this.formatNumber(totalSelfAmount);
                
                const partialBurdenValue = parseInt(document.getElementById('partialBurden').textContent.replace(/,/g, '')) || 0;
                const totalPayValue = partialBurdenValue + totalSelfAmount;
                document.getElementById('totalPay').textContent = totalPayValue === 0 ? '' : this.formatNumber(totalPayValue);

                selfPayRow.style.display = totalSelfAmount > 0 ? 'flex' : 'none';
            }

            // 更新費率和額度
            updateRatesAndQuotas() {
                if (this.state.isEditMode) return;
                
                const cmsLevel = document.querySelector('input[name="cmsLevel"]:checked')?.value;
                if (cmsLevel) {
                    const paymentQuota = this.cmsPaymentMap[cmsLevel] || 0;
                    document.getElementById('paymentQuota').textContent = paymentQuota ? this.formatNumber(paymentQuota) : '';
                } else {
                    document.getElementById('paymentQuota').textContent = '';
                }
                
                this.recalculateTotals();
                this.checkBudget();
            }

            // 檢查預算狀態
            checkBudget() {
                if (this.state.isEditMode) return;

                const quotaTotal = parseInt(document.getElementById('quotaTotal').textContent.replace(/,/g, '')) || 0;
                const usageQuota = parseInt(document.getElementById('usageQuota').value.replace(/,/g, '')) || 0;
                const paymentQuota = parseInt(document.getElementById('paymentQuota').textContent.replace(/,/g, '')) || 0;
                const totalAvailable = usageQuota + paymentQuota;
                const remainingQuota = totalAvailable - quotaTotal;

                const warningContainer = document.querySelector('.warning-container');
                let hasProposedAmount = false;
                
                document.querySelectorAll('.proposed-amount').forEach(cell => {
                    if (cell.textContent.trim() !== '') {
                        hasProposedAmount = true;
                    }
                });

                if (remainingQuota < 0 && !hasProposedAmount) {
                    warningContainer.style.display = 'block';
                    document.getElementById('overBudgetWarning').style.display = 'block';
                    document.getElementById('excessAllocationBtn').style.display = 'block';
                } else {
                    warningContainer.style.display = 'none';
                    document.getElementById('overBudgetWarning').style.display = 'none';
                    document.getElementById('excessAllocationBtn').style.display = 'none';
                }
            }

            // 檢查更新按鈕顯示
            checkUpdateButtonDisplay() {
                const updateBtn = document.getElementById('updateBtn');
                const proposedElements = document.querySelectorAll('.proposed-count');
                let hasProposedValues = false;
                
                proposedElements.forEach(element => {
                    if (element.textContent.trim() !== '') {
                        hasProposedValues = true;
                    }
                });

                if (this.state.hasPerformedExcessAllocation && hasProposedValues && this.state.tableHasChanged) {
                    updateBtn.style.display = 'block';
                } else {
                    updateBtn.style.display = 'none';
                }
            }

            // 更新表格欄位可見性
            updateTableColumnsVisibility() {
                let hasProposedValues = false;
                let hasSelfPayValues = false;
                
                document.querySelectorAll('#serviceTableBody tr').forEach(row => {
                    const proposedCount = row.querySelector('.proposed-count').textContent.trim();
                    const selfCount = row.querySelector('.self-count').textContent.trim();
                    if (proposedCount !== '') hasProposedValues = true;
                    if (selfCount !== '') hasSelfPayValues = true;
                });

                // 更新欄位顯示狀態
                this.toggleColumnVisibility('.proposed-count-col', hasProposedValues);
                this.toggleColumnVisibility('.proposed-amount-col', hasProposedValues);
                this.toggleColumnVisibility('.self-count-col', hasSelfPayValues);
                this.toggleColumnVisibility('.self-amount-col', hasSelfPayValues);
            }

            // 切換欄位可見性
            toggleColumnVisibility(className, show) {
                document.querySelectorAll(className).forEach(col => {
                    col.style.display = show ? '' : 'none';
                });
            }

            // 儲存費率設定
            saveRateSettings() {
                this.state.isRateEditMode = false;
                document.getElementById('saveRateBtn').style.display = 'none';
                document.getElementById('editRateBtn').style.display = 'block';
                
                const bonusItems = ['AA05', 'AA06', 'AA08', 'AA09', 'AA11'];
                bonusItems.forEach(code => {
                    const priceInput = document.getElementById(`rate_price_${code}`);
                    if (priceInput?.value) {
                        this.setCookie(`rate_price_${code}`, priceInput.value.replace(/,/g, ''));
                    }
                });

                // 轉換輸入框為文字顯示
                document.querySelectorAll('.price-input, input[id^="rate_count_"]').forEach(input => {
                    const value = input.value;
                    const cell = input.parentElement;
                    cell.innerHTML = value === '' ? '' : value;
                    cell.classList.add('text-right');
                });

                this.recalculateTotals();
                this.showToast('費率設定已儲存', 'success');
            }

            // 編輯費率設定
            editRateSettings() {
                this.state.isRateEditMode = true;
                document.getElementById('saveRateBtn').style.display = 'block';
                document.getElementById('editRateBtn').style.display = 'none';

                // 保存當前值
                const rateValues = {};
                document.querySelectorAll('.bonus-table tbody tr').forEach(row => {
                    const item = row.cells[0].textContent;
                    const price = row.cells[1].textContent.replace(/,/g, '') || '';
                    const count = row.cells[2].textContent || '';
                    rateValues[item] = { price, count };
                });

                // 轉換為輸入框
                document.querySelectorAll('.bonus-table tbody tr').forEach(row => {
                    const item = row.cells[0].textContent;
                    let priceValue = rateValues[item].price;
                    if (priceValue) {
                        priceValue = this.formatNumber(parseInt(priceValue));
                    }
                    
                    row.cells[1].innerHTML = `<input type="text" id="rate_price_${item}" value="${priceValue}" class="price-input" aria-label="${item}價格">`;
                    row.cells[2].innerHTML = `<input type="number" id="rate_count_${item}" min="0" value="${rateValues[item].count}" class="text-right" aria-label="${item}次數">`;
                });

                this.setupRateInputListeners();
                this.loadPricesFromStorage();
                
                document.getElementById('monthlyAmount').textContent = "請儲存加成次數";
                document.getElementById('monthlyAmount').classList.add('red-text');
            }

            // 設定費率輸入監聽器
            setupRateInputListeners() {
                document.querySelectorAll('.price-input').forEach(input => {
                    input.addEventListener('input', (e) => {
                        this.formatNumberInput(e);
                        if (!this.state.isEditMode) this.recalculateTotals();
                    });
                });

                document.querySelectorAll('input[id^="rate_count_"]').forEach(input => {
                    input.addEventListener('input', (e) => {
                        if (e.target.value === '0') e.target.value = '';
                        if (!this.state.isEditMode) this.recalculateTotals();
                    });
                });
            }

            // 執行優化分配
            runOptimization() {
                this.showProgress(0);
                this.showToast('正在計算最佳分配...', 'info');
                
                setTimeout(() => {
                    try {
                        const data = this.prepareOptimizationData();
                        this.showProgress(30);
                        
                        const result = this.optimizeServiceTimes(data);
                        this.showProgress(80);
                        
                        if (result.success && result.needOptimization) {
                            this.saveOriginalValues();
                            this.displayOptimizationResults(result);
                            this.hideWarningContainer();
                            this.state.hasPerformedExcessAllocation = true;
                            this.state.tableHasChanged = false;
                            this.updateTableColumnsVisibility();
                            this.showToast('超額分配完成！', 'success');
                        } else {
                            this.showToast(result.message || '無需進行優化分配', 'info');
                        }
                    } catch (error) {
                        console.error('優化計算錯誤:', error);
                        this.showToast('計算過程發生錯誤，請重試', 'error');
                    } finally {
                        this.showProgress(100);
                        setTimeout(() => this.hideProgress(), 500);
                    }
                }, 100);
            }

            // 隱藏警告容器
            hideWarningContainer() {
                document.querySelector('.warning-container').style.display = 'none';
                document.getElementById('overBudgetWarning').style.display = 'none';
                document.getElementById('excessAllocationBtn').style.display = 'none';
                document.querySelector('.partial-burden-row').style.display = 'flex';
            }

            // 清除最佳化結果
            clearOptimizationResults() {
                document.querySelectorAll('.proposed-count, .proposed-amount, .burden-amount, .self-count, .self-amount').forEach(cell => {
                    cell.textContent = '';
                });
                
                this.state.hasPerformedExcessAllocation = false;
                this.state.tableHasChanged = false;
                this.recalculateTotals();
                this.checkBudget();
                document.getElementById('updateBtn').style.display = 'none';
                this.updateTableColumnsVisibility();
                this.showToast('已清除分配結果', 'info');
            }

            // 清除所有資料
            clearData() {
                if (!confirm('確定要重置所有資料嗎？此操作無法復原。')) {
                    return;
                }

                // 清除服務項目表格
                document.querySelectorAll('#serviceTableBody tr').forEach(row => {
                    row.querySelector('.weekly-count').value = '';
                    row.querySelector('.monthly-count').textContent = '';
                    row.querySelector('.total-count').value = '';
                    row.querySelector('.usage-amount').textContent = '';
                    row.querySelector('.basic-burden').textContent = '';
                    row.querySelector('.proposed-count').textContent = '';
                    row.querySelector('.proposed-amount').textContent = '';
                    row.querySelector('.burden-amount').textContent = '';
                    row.querySelector('.self-count').textContent = '';
                    row.querySelector('.self-amount').textContent = '';
                });

                // 清除其他欄位
                document.getElementById('usageQuota').value = '';
                document.querySelectorAll('input[name="cmsLevel"]').forEach(radio => {
                    radio.checked = false;
                });
                document.getElementById('paymentQuota').textContent = '';

                // 清除加成次數
                if (this.state.isRateEditMode) {
                    document.querySelectorAll('input[id^="rate_count_"]').forEach(input => {
                        input.value = '';
                    });
                } else {
                    document.querySelectorAll('.bonus-table tbody tr').forEach(row => {
                        row.cells[2].textContent = '';
                    });
                }

                // 重置狀態
                this.state.hasPerformedExcessAllocation = false;
                this.state.tableHasChanged = false;
                this.recalculateTotals();
                
                // 隱藏相關UI元素
                document.querySelector('.warning-container').style.display = 'none';
                document.getElementById('overBudgetWarning').style.display = 'none';
                document.getElementById('excessAllocationBtn').style.display = 'none';
                document.querySelector('.partial-burden-row').style.display = 'flex';
                document.querySelector('.self-pay-row').style.display = 'none';
                document.getElementById('updateBtn').style.display = 'none';
                this.updateTableColumnsVisibility();

                this.showToast('所有資料已重置', 'success');
            }

            // 響應式布局調整
            adjustResponsiveLayout() {
                const tableWidth = document.getElementById('serviceTable').offsetWidth;
                if (window.innerWidth <= 1200) {
                    document.querySelectorAll('.config-item').forEach(item => {
                        item.style.width = tableWidth + 'px';
                    });
                } else {
                    document.querySelectorAll('.config-item').forEach(item => {
                        item.style.width = '';
                    });
                }
                this.updateStickyColumnPositions();
            }

            // 更新固定欄位位置
            updateStickyColumnPositions() {
                if (window.innerWidth <= 768) {
                    const firstColumns = document.querySelectorAll('#serviceTable th:first-child, #serviceTable td:first-child');
                    if (firstColumns.length > 0) {
                        const firstColumnWidth = firstColumns[0].offsetWidth;
                        document.querySelectorAll('#serviceTable th:nth-child(2), #serviceTable td:nth-child(2)').forEach(element => {
                            element.style.left = firstColumnWidth + 'px';
                        });
                    }
                }
            }

            // 準備優化數據 (簡化版本，保留核心邏輯)
            prepareOptimizationData() {
                const usageQuotaStr = document.getElementById('usageQuota').value;
                const cmsLevel = document.querySelector('input[name="cmsLevel"]:checked')?.value;
                const paymentQuota = cmsLevel ? (this.cmsPaymentMap[cmsLevel] || 0) : 0;
                
                const identityType = document.querySelector('input[name="identityType"]:checked')?.value || "一般戶";
                
                const data = {
                    E4: parseInt(usageQuotaStr.replace(/,/g, '')) || 0,
                    D5: paymentQuota,
                    A10: identityType,
                    B10: this.identityRateMap[identityType] || 0,
                    items1to23: [],
                    items24to25: []
                };

                // 收集服務項目數據
                const rows = document.querySelectorAll('#serviceTableBody tr');
                rows.forEach((row, index) => {
                    const code = row.getAttribute('data-code');
                    const priceElement = row.querySelector('td:nth-child(2)');
                    const price = parseInt(priceElement.textContent.replace(/,/g, '')) || 0;
                    const monthlyCount = parseInt(row.querySelector('.monthly-count').textContent) || 0;
                    const totalCount = parseInt(row.querySelector('.total-count').value) || 0;
                    const usageAmount = parseInt(row.querySelector('.usage-amount').textContent.replace(/,/g, '')) || 0;

                    if (usageAmount > 0) {
                        const item = {
                            rowNum: index + 11,
                            code,
                            price,
                            monthlyCount,
                            totalCount,
                            usageAmount,
                            totalItemCount: monthlyCount + totalCount,
                            percentRate: this.identityRateMap[identityType] || 0
                        };

                        if (index < 23) {
                            data.items1to23.push(item);
                        } else {
                            data.items24to25.push(item);
                        }
                    }
                });

                return data;
            }

            // 優化服務時間分配 (核心算法)
            optimizeServiceTimes(data) {
                if (!data.items1to23 || data.items1to23.length === 0) {
                    return { success: false, message: "沒有找到有效的服務項目。", needOptimization: false };
                }

                const totalUsage1to23 = data.items1to23.reduce((sum, item) => sum + item.usageAmount, 0);
                const availableAmount = data.E4 + data.D5;

                if (totalUsage1to23 <= availableAmount) {
                    return { success: true, message: "使用額度未超過可用額度，不需要優化。", needOptimization: false };
                }

                // 簡化的貪婪算法
                const solution1to23 = [];
                const solution24to25 = [];
                const amountToReduce = totalUsage1to23 - availableAmount;

                // 按價格排序，優先減少高價項目
                const sortedItems = [...data.items1to23].sort((a, b) => b.price - a.price);
                let currentAmountReduced = 0;

                // 為每個項目計算優化後的數量
                const optimizedCounts = {};
                data.items1to23.forEach(item => {
                    optimizedCounts[item.rowNum] = item.totalItemCount;
                });

                // 減少高價項目直到滿足預算
                for (const item of sortedItems) {
                    while (optimizedCounts[item.rowNum] > 1 && currentAmountReduced < amountToReduce) {
                        optimizedCounts[item.rowNum]--;
                        currentAmountReduced += item.price;
                        
                        if (currentAmountReduced >= amountToReduce) break;
                    }
                    if (currentAmountReduced >= amountToReduce) break;
                }

                // 生成解決方案
                data.items1to23.forEach(item => {
                    solution1to23.push({
                        rowNum: item.rowNum,
                        optimizedCount: optimizedCounts[item.rowNum]
                    });
                });

                if (data.items24to25) {
                    data.items24to25.forEach(item => {
                        solution24to25.push({
                            rowNum: item.rowNum,
                            optimizedCount: item.totalItemCount
                        });
                    });
                }

                return {
                    success: true,
                    needOptimization: true,
                    message: "超額分配已完成！",
                    solution1to23,
                    solution24to25
                };
            }

            // 顯示優化結果
            displayOptimizationResults(result) {
                this.clearOptimizationResults();

                if (result.solution1to23?.length > 0) {
                    result.solution1to23.forEach(item => {
                        this.updateRowWithOptimizationResult(item);
                    });
                }

                if (result.solution24to25?.length > 0) {
                    result.solution24to25.forEach(item => {
                        this.updateRowWithOptimizationResult(item);
                    });
                }

                this.recalculateTotals();
            }

            // 更新行的優化結果
            updateRowWithOptimizationResult(item) {
                const rowIndex = item.rowNum - 11;
                const rows = document.querySelectorAll('#serviceTableBody tr');
                
                if (rowIndex >= 0 && rowIndex < rows.length) {
                    const row = rows[rowIndex];
                    const priceElement = row.querySelector('td:nth-child(2)');
                    const price = parseInt(priceElement.textContent.replace(/,/g, '')) || 0;
                    const monthlyCount = parseInt(row.querySelector('.monthly-count').textContent) || 0;
                    const totalCount = parseInt(row.querySelector('.total-count').value) || 0;
                    const originalCount = monthlyCount + totalCount;
                    const optimizedCount = item.optimizedCount;
                    const optimizedAmount = optimizedCount * price;

                    // 計算負擔
                    const identityType = document.querySelector('input[name="identityType"]:checked')?.value || "一般戶";
                    const percentRate = this.identityRateMap[identityType] || 0;
                    const unitBurden = Math.floor(price * percentRate);
                    const burdenAmount = optimizedCount * unitBurden;

                    // 計算自費
                    const selfCount = originalCount - optimizedCount;
                    const selfAmount = selfCount * price;

                    // 更新顯示
                    row.querySelector('.proposed-count').textContent = optimizedCount || '';
                    row.querySelector('.proposed-amount').textContent = optimizedAmount ? this.formatNumber(optimizedAmount) : '';
                    row.querySelector('.burden-amount').textContent = burdenAmount ? this.formatNumber(burdenAmount) : '';

                    if (selfCount > 0) {
                        row.querySelector('.self-count').textContent = selfCount;
                        row.querySelector('.self-amount').textContent = this.formatNumber(selfAmount);
                    } else {
                        row.querySelector('.self-count').textContent = '';
                        row.querySelector('.self-amount').textContent = '';
                    }
                }
            }

            // 保存原始值
            saveOriginalValues() {
                document.querySelectorAll('#serviceTableBody tr').forEach(row => {
                    const rowCode = row.getAttribute('data-code');
                    const weeklyCount = row.querySelector('.weekly-count').value;
                    const totalCount = row.querySelector('.total-count').value;
                    this.state.originalValues[rowCode] = { weeklyCount, totalCount };
                });
            }

            // UI 輔助方法
            showProgress(percentage) {
                const container = document.getElementById('progressContainer');
                const fill = document.getElementById('progressFill');
                container.style.display = 'block';
                fill.style.width = percentage + '%';
            }

            hideProgress() {
                document.getElementById('progressContainer').style.display = 'none';
            }

            showLoading() {
                document.getElementById('loadingIndicator').style.display = 'block';
            }

            hideLoading() {
                document.getElementById('loadingIndicator').style.display = 'none';
            }

            showToast(message, type = 'info') {
                // 移除現有的 toast
                const existingToast = document.querySelector('.toast');
                if (existingToast) {
                    existingToast.remove();
                }

                const toast = document.createElement('div');
                toast.className = `toast ${type}`;
                toast.textContent = message;
                document.body.appendChild(toast);

                // 顯示動畫
                setTimeout(() => toast.classList.add('show'), 100);

                // 自動隱藏
                setTimeout(() => {
                    toast.classList.remove('show');
                    setTimeout(() => toast.remove(), 300);
                }, 3000);
            }
        }

        // 安全保護層 (簡化版本)
        (function() {
            'use strict';
            
            // 防止iframe嵌入
            if (top !== self) {
                top.location = self.location;
            }

            // 監控複製事件
            document.addEventListener('copy', function(e) {
                if (e.target.tagName !== 'INPUT' && e.target.tagName !== 'TEXTAREA') {
                    e.clipboardData.setData('text/plain', '© 億家人居家長照機構 - 內容受版權保護');
                    e.preventDefault();
                }
            });

            // 基本開發者工具偵測
            let devtoolsOpen = false;
            const threshold = 160;
            
            setInterval(function() {
                if (window.outerHeight - window.innerHeight > threshold || 
                    window.outerWidth - window.innerWidth > threshold) {
                    if (!devtoolsOpen) {
                        devtoolsOpen = true;
                        console.clear();
                        console.log('%c⚠️ 安全提示', 'color: red; font-size: 20px; font-weight: bold;');
                        console.log('%c此系統受版權保護，請勿嘗試查看或複製原始碼。', 'color: red; font-size: 14px;');
                        console.log('%c© 2023-2025 億家人居家長照機構', 'color: blue; font-size: 12px;');
                    }
                } else {
                    devtoolsOpen = false;
                }
            }, 500);
            
            // 定期清理控制台
            setInterval(function() {
                if (devtoolsOpen) {
                    console.clear();
                    console.log('%c系統保護中...', 'color: green; font-size: 12px;');
                }
            }, 3000);
        })();

        // 應用程式啟動
        document.addEventListener('DOMContentLoaded', function() {
            // 顯示載入動畫
            document.getElementById('loadingIndicator').style.display = 'block';
            
            // 初始化應用程式
            window.quotaApp = new QuotaCalculator();
        });

        // 服務工作者註冊 (PWA 支援)
        if ('serviceWorker' in navigator) {
            window.addEventListener('load', function() {
                navigator.serviceWorker.register('/sw.js')
                .then(function(registration) {
                    console.log('ServiceWorker registration successful');
                })
                .catch(function(err) {
                    console.log('ServiceWorker registration failed');
                });
            });
        }
    </script>
</body>
</html>
