# EduMeetOS

开源无人机与机器狗操作系统。  
Open-source OS for drones and robotic dogs.

## 版本 Editions
- 家庭版 Home
- 教育版 Education  
- 会议版 Meeting
- 开发者版 Developer

## 项目 Project
- [官网 Website](https://你的用户名.github.io)
- 会议无人机 Meeting Drone
- 导盲机器狗 Guide Dog (coming soon)

## 加入我们 Join
开源，等你来。
<!-- 页脚区域 -->
<footer style="background: #f2f2f2; color: #333; padding: 2rem 1rem 1rem; font-family: system-ui, -apple-system, sans-serif; border-top: 1px solid #ddd;">
    <div style="max-width: 1200px; margin: 0 auto;">

        <!-- 第一行：链接网格 -->
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 2rem; font-size: 0.85rem;">
            <!-- 列1：系统版本 -->
            <div>
                <div style="font-weight: 600; margin-bottom: 1rem;">EduMeetOS</div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">家庭版</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">教育版</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">会议版</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">开发者版</a></div>
            </div>
            <!-- 列2：硬件设备 -->
            <div>
                <div style="font-weight: 600; margin-bottom: 1rem;">设备</div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">会议无人机</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">导盲机器狗</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">教育机器人</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">开发者套件</a></div>
            </div>
            <!-- 列3：社区与支持 -->
            <div>
                <div style="font-weight: 600; margin-bottom: 1rem;">社区</div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">GitHub</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">加入我们</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">文档</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">开发者论坛</a></div>
            </div>
            <!-- 列4：关于 -->
            <div>
                <div style="font-weight: 600; margin-bottom: 1rem;">关于</div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">项目介绍</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">开源协议</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">团队成员</a></div>
                <div><a href="#" style="color: #555; text-decoration: none; display: block; margin-bottom: 0.5rem;">联系</a></div>
            </div>
        </div>

        <!-- 第二行：语言 + 版权信息 -->
        <div style="border-top: 1px solid #ccc; margin-top: 2rem; padding-top: 1rem; font-size: 0.75rem; color: #666; display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center;">
            <div style="display: flex; gap: 1rem; flex-wrap: wrap;">
                <span>中文(简体)</span>
                <span>English</span>
                <span>Español</span>
                <span>Français</span>
            </div>
            <div style="display: flex; gap: 1.5rem; flex-wrap: wrap;">
                <a href="#" style="color: #666; text-decoration: none;">隐私声明</a>
                <a href="#" style="color: #666; text-decoration: none;">使用条款</a>
                <a href="#" style="color: #666; text-decoration: none;">商标</a>
                <span>© 2026 EduMeetOS · 开源社区</span>
            </div>
        </div>

    </div>
</footer>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EduMeetOS · 欢迎你</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: #0a0a0a;
            color: #fff;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 1rem;
        }
        .container {
            max-width: 800px;
            width: 100%;
            background: #111;
            border-radius: 48px;
            padding: 2.5rem 2rem;
            box-shadow: 0 30px 60px rgba(0,0,0,0.8);
            border: 1px solid #222;
        }
        .earth-container {
            display: flex;
            justify-content: center;
            margin-bottom: 2rem;
            perspective: 800px;
        }
        .earth {
            width: 120px;
            height: 120px;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="50" cy="50" r="48" fill="%232a6f97" stroke="%234d9eff" stroke-width="0.5"/><path d="M20 30 Q40 20 60 30 T90 40" stroke="%236b8cff" fill="none" stroke-width="1.5"/><path d="M15 60 Q40 75 70 60" stroke="%236b8cff" fill="none" stroke-width="1.5"/><circle cx="50" cy="50" r="4" fill="%23ffd966" filter="url(%23glow)"/><defs><filter id="glow"><feGaussianBlur stdDeviation="2" result="coloredBlur"/><feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs></svg>') no-repeat center;
            background-size: contain;
            animation: gentleRock 8s ease-in-out infinite;
            transform-origin: center;
        }
        @keyframes gentleRock {
            0% { transform: rotate(0deg) scale(1); }
            25% { transform: rotate(5deg) scale(1.02); }
            50% { transform: rotate(0deg) scale(1); }
            75% { transform: rotate(-5deg) scale(0.98); }
            100% { transform: rotate(0deg) scale(1); }
        }
        .step-indicator {
            display: flex;
            justify-content: center;
            gap: 0.75rem;
            margin-bottom: 2rem;
        }
        .step-dot {
            width: 10px;
            height: 10px;
            border-radius: 10px;
            background: #333;
            transition: all 0.3s ease;
        }
        .step-dot.active {
            background: #fff;
            width: 24px;
        }
        .step-dot.completed {
            background: #4d9eff;
        }
        .step {
            display: none;
            animation: fadeIn 0.3s ease;
        }
        .step.active-step {
            display: block;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .question {
            font-size: 1.8rem;
            font-weight: 500;
            margin-bottom: 1.5rem;
            letter-spacing: -0.02em;
        }
        .options {
            display: flex;
            flex-direction: column;
            gap: 0.75rem;
            margin-bottom: 2rem;
        }
        .option-item {
            background: #1a1a1a;
            border: 1px solid #333;
            border-radius: 40px;
            padding: 0.8rem 1.5rem;
            font-size: 1.2rem;
            cursor: pointer;
            transition: background 0.2s, border-color 0.2s;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        .option-item:hover {
            background: #222;
            border-color: #555;
        }
        .option-item.selected {
            border-color: #fff;
            background: #2a2a2a;
        }
        .option-item .check {
            opacity: 0;
            color: #4d9eff;
            transition: opacity 0.2s;
        }
        .option-item.selected .check {
            opacity: 1;
        }
        .locate-btn {
            background: transparent;
            border: 1px solid #444;
            color: #ccc;
            padding: 0.5rem 1rem;
            border-radius: 40px;
            font-size: 0.9rem;
            margin-top: 0.5rem;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            transition: background 0.2s;
        }
        .locate-btn:hover {
            background: #222;
            border-color: #666;
        }
        .navigation {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 2rem;
        }
        .btn {
            padding: 0.8rem 2rem;
            border-radius: 40px;
            font-size: 1rem;
            font-weight: 500;
            cursor: pointer;
            border: none;
            transition: all 0.2s;
            background: transparent;
            color: #fff;
            border: 1px solid #555;
        }
        .btn.primary {
            background: #fff;
            color: #0a0a0a;
            border: 1px solid #fff;
        }
        .btn.primary:hover {
            background: #eee;
        }
        .btn:disabled {
            opacity: 0.3;
            cursor: not-allowed;
        }
        .btn.secondary {
            border: 1px solid #444;
            color: #aaa;
        }
        .btn.secondary:hover {
            border-color: #666;
            color: #fff;
        }
        .response-message {
            background: rgba(255,255,255,0.03);
            border-left: 4px solid #fff;
            padding: 1.5rem;
            border-radius: 12px;
            margin-top: 1.5rem;
            line-height: 1.6;
            color: #ddd;
            animation: fadeIn 0.3s ease;
        }
        .response-message strong {
            color: #fff;
            display: block;
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
        }
        .small-note {
            color: #666;
            font-size: 0.85rem;
            margin-top: 0.5rem;
        }
        @media (max-width: 600px) {
            .container { padding: 1.5rem; }
            .question { font-size: 1.5rem; }
            .option-item { font-size: 1rem; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="earth-container">
            <div class="earth"></div>
        </div>

        <div class="step-indicator">
            <div class="step-dot active" id="step1-dot"></div>
            <div class="step-dot" id="step2-dot"></div>
            <div class="step-dot" id="step3-dot"></div>
        </div>

        <!-- 步骤1: 国家选择 -->
        <div class="step active-step" id="step1">
            <div class="question">Where are you building from?</div>
            <div class="options" id="country-options">
                <!-- 动态生成国家选项，也可直接写静态 -->
            </div>
            <button class="locate-btn" id="detect-location">
                <span>📍</span> Detect automatically
            </button>
            <div class="navigation">
                <span></span>
                <button class="btn primary" id="step1-next" disabled>Next</button>
            </div>
        </div>

        <!-- 步骤2: 行业选择 -->
        <div class="step" id="step2">
            <div class="question">What brings you here?</div>
            <div class="options" id="industry-options">
                <!-- 动态生成行业选项 -->
            </div>
            <div class="navigation">
                <button class="btn secondary" id="step2-back">Back</button>
                <button class="btn primary" id="step2-next" disabled>Next</button>
            </div>
        </div>

        <!-- 步骤3: 个性化信息 -->
        <div class="step" id="step3">
            <div class="question">Here's something for you</div>
            <div id="personalized-message" class="response-message">
                <!-- 内容动态填充 -->
            </div>
            <div class="navigation">
                <button class="btn secondary" id="step3-back">Back</button>
                <button class="btn primary" id="step3-done">Return to Home</button>
            </div>
        </div>

        <div class="small-note">
            * No data is stored. This is just a greeting.
        </div>
    </div>

    <script>
        (function() {
            // 数据
            const countries = [
                { code: 'us', name: 'United States' },
                { code: 'uk', name: 'United Kingdom' },
                { code: 'cn', name: 'China (简体中文)' },
                { code: 'jp', name: 'Japan' },
                { code: 'de', name: 'Germany' },
                { code: 'fr', name: 'France' },
                { code: 'in', name: 'India' },
                { code: 'br', name: 'Brazil' },
                { code: 'other', name: 'Other' }
            ];

            const industries = [
                { id: 'it', name: 'IT / Developer' },
                { id: 'teacher', name: 'Teacher / Educator' },
                { id: 'lawyer', name: 'Lawyer' },
                { id: 'designer', name: 'Designer' },
                { id: 'photographer', name: 'Photographer / Content creator' },
                { id: 'other', name: 'Other' }
            ];

            // 行业对应的文案
            const messages = {
                it: {
                    title: 'Welcome, developer!',
                    body: 'We are actively looking for developers like you to join our open-source community. Contribute to EduMeetOS and help shape the future of drone and robotic dog operating systems.'
                },
                teacher: {
                    title: 'Hello, educator!',
                    body: 'EduMeet Education Edition is in the works. We are designing tools to make robotics accessible in classrooms. Leave your email to get early access updates.'
                },
                lawyer: {
                    title: 'Thank you for your interest',
                    body: 'We currently don\'t have a specialized version for legal professionals. However, we welcome your perspective on compliance and ethics. Feel free to reach out.'
                },
                designer: {
                    title: 'Hey designer!',
                    body: 'We value great design! Our interface is minimal, but we are always looking for feedback from designers to improve user experience. Want to collaborate?'
                },
                photographer: {
                    title: 'Hi photographer!',
                    body: 'The Meeting Edition drone is perfect for capturing events from unique angles. Let us know if you\'d like to test it for your photography projects.'
                },
                other: {
                    title: 'Thanks for stopping by',
                    body: 'Thank you for your interest in EduMeetOS. We are building for everyone, and we\'d love to hear more about how you might use our system. Please reach out to us directly.'
                }
            };

            // 当前状态
            let currentStep = 1;
            let selectedCountry = null;
            let selectedIndustry = null;

            // DOM 元素
            const step1 = document.getElementById('step1');
            const step2 = document.getElementById('step2');
            const step3 = document.getElementById('step3');
            const step1Dot = document.getElementById('step1-dot');
            const step2Dot = document.getElementById('step2-dot');
            const step3Dot = document.getElementById('step3-dot');
            const step1Next = document.getElementById('step1-next');
            const step2Back = document.getElementById('step2-back');
            const step2Next = document.getElementById('step2-next');
            const step3Back = document.getElementById('step3-back');
            const step3Done = document.getElementById('step3-done');
            const detectBtn = document.getElementById('detect-location');
            const countryOptionsDiv = document.getElementById('country-options');
            const industryOptionsDiv = document.getElementById('industry-options');
            const messageDiv = document.getElementById('personalized-message');

            // 渲染国家选项
            function renderCountries() {
                countryOptionsDiv.innerHTML = '';
                countries.forEach(country => {
                    const div = document.createElement('div');
                    div.className = 'option-item';
                    div.dataset.code = country.code;
                    div.innerHTML = `
                        <span>${country.name}</span>
                        <span class="check">✓</span>
                    `;
                    div.addEventListener('click', () => {
                        // 移除其他选中样式
                        document.querySelectorAll('#country-options .option-item').forEach(el => el.classList.remove('selected'));
                        div.classList.add('selected');
                        selectedCountry = country.code;
                        step1Next.disabled = false;
                    });
                    countryOptionsDiv.appendChild(div);
                });
            }

            // 渲染行业选项
            function renderIndustries() {
                industryOptionsDiv.innerHTML = '';
                industries.forEach(ind => {
                    const div = document.createElement('div');
                    div.className = 'option-item';
                    div.dataset.id = ind.id;
                    div.innerHTML = `
                        <span>${ind.name}</span>
                        <span class="check">✓</span>
                    `;
                    div.addEventListener('click', () => {
                        document.querySelectorAll('#industry-options .option-item').forEach(el => el.classList.remove('selected'));
                        div.classList.add('selected');
                        selectedIndustry = ind.id;
                        step2Next.disabled = false;
                    });
                    industryOptionsDiv.appendChild(div);
                });
            }

            // 更新步骤显示
            function goToStep(step) {
                currentStep = step;
                // 隐藏所有步骤
                step1.classList.remove('active-step');
                step2.classList.remove('active-step');
                step3.classList.remove('active-step');
                // 显示当前步骤
                if (step === 1) {
                    step1.classList.add('active-step');
                } else if (step === 2) {
                    step2.classList.add('active-step');
                } else if (step === 3) {
                    step3.classList.add('active-step');
                    // 生成个性化信息
                    const msg = messages[selectedIndustry] || messages.other;
                    messageDiv.innerHTML = `<strong>${msg.title}</strong><p>${msg.body}</p>`;
                    if (selectedCountry) {
                        const countryName = countries.find(c => c.code === selectedCountry)?.name || 'your country';
                        messageDiv.innerHTML += `<p style="margin-top:1rem; color:#888;">From ${countryName}</p>`;
                    }
                }
                // 更新圆点
                step1Dot.className = 'step-dot' + (step === 1 ? ' active' : (step > 1 ? ' completed' : ''));
                step2Dot.className = 'step-dot' + (step === 2 ? ' active' : (step > 2 ? ' completed' : ''));
                step3Dot.className = 'step-dot' + (step === 3 ? ' active' : '');
            }

            // 定位功能（模拟）
            detectBtn.addEventListener('click', () => {
                // 这里可以用 Geolocation API，为了演示，我们模拟一个随机国家
                if (navigator.geolocation) {
                    navigator.geolocation.getCurrentPosition(
                        (position) => {
                            // 通常需要反向地理编码，这里简化：随机选择一个国家
                            const randomIndex = Math.floor(Math.random() * (countries.length - 1)); // 避免选到 other
                            const randomCountry = countries[randomIndex];
                            // 高亮对应选项
                            document.querySelectorAll('#country-options .option-item').forEach(el => {
                                if (el.dataset.code === randomCountry.code) {
                                    el.classList.add('selected');
                                    selectedCountry = randomCountry.code;
                                    step1Next.disabled = false;
                                } else {
                                    el.classList.remove('selected');
                                }
                            });
                        },
                        (error) => {
                            alert('Unable to detect location. Please select manually.');
                        }
                    );
                } else {
                    alert('Geolocation not supported. Please select manually.');
                }
            });

            // 按钮事件
            step1Next.addEventListener('click', () => {
                if (selectedCountry) goToStep(2);
            });
            step2Back.addEventListener('click', () => {
                goToStep(1);
            });
            step2Next.addEventListener('click', () => {
                if (selectedIndustry) goToStep(3);
            });
            step3Back.addEventListener('click', () => {
                goToStep(2);
            });
            step3Done.addEventListener('click', () => {
                // 返回首页或刷新
                window.location.href = '/'; // 或者你的首页地址
            });

            // 初始化
            renderCountries();
            renderIndustries();
            goToStep(1);
        })();
    </script>
</body>
</html>