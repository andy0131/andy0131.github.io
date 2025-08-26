<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>社區心理防衛與內部穩定指引</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;600;700;800&family=Noto+Sans+TC:wght@300;400;500;600;700&display=swap');
        body { 
            font-family: 'Noto Sans TC', 'Orbitron', monospace; 
            background: #0a0f0a;
            color: #00ff41;
        }
        .gradient-bg { 
            background: linear-gradient(135deg, #0a0f0a 0%, #1a2f1a 50%, #0f1f0f 100%);
            border-bottom: 2px solid #00ff41;
            position: relative;
        }
        .gradient-bg::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: 
                radial-gradient(circle at 20% 20%, rgba(0,255,65,0.1) 0%, transparent 50%),
                radial-gradient(circle at 80% 80%, rgba(0,255,65,0.05) 0%, transparent 50%);
        }
        .section-card { 
            transition: all 0.3s ease;
            background: rgba(10,15,10,0.9) !important;
            border: 1px solid #00ff41;
            box-shadow: 0 0 20px rgba(0,255,65,0.2);
        }
        .section-card:hover { 
            transform: translateY(-2px); 
            box-shadow: 0 0 30px rgba(0,255,65,0.4);
            border-color: #00ff88;
        }
        .warning-pulse { 
            animation: pulse 2s infinite;
            border: 2px solid #ff4444 !important;
            background: rgba(255,68,68,0.1) !important;
        }
        @keyframes pulse {
            0%, 100% { 
                opacity: 1; 
                box-shadow: 0 0 20px rgba(255,68,68,0.5);
            }
            50% { 
                opacity: 0.8;
                box-shadow: 0 0 40px rgba(255,68,68,0.8);
            }
        }
        .step-number {
            background: linear-gradient(45deg, #00ff41, #00cc33);
            color: #0a0f0a;
            width: 32px;
            height: 32px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin-right: 12px;
            flex-shrink: 0;
            font-family: 'Orbitron', monospace;
            box-shadow: 0 0 10px rgba(0,255,65,0.5);
        }
        .phase-indicator {
            background: linear-gradient(45deg, #ff6600, #ff4400);
            color: #0a0f0a;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 600;
            margin-bottom: 8px;
            display: inline-block;
            font-family: 'Orbitron', monospace;
            box-shadow: 0 0 10px rgba(255,102,0,0.5);
        }
        .radar-grid {
            background-image: 
                linear-gradient(rgba(0,255,65,0.1) 1px, transparent 1px),
                linear-gradient(90deg, rgba(0,255,65,0.1) 1px, transparent 1px);
            background-size: 20px 20px;
        }
        .military-text {
            font-family: 'Orbitron', monospace;
            text-shadow: 0 0 10px rgba(0,255,65,0.5);
        }
        .section-number {
            background: linear-gradient(45deg, #00ff41, #00cc33);
            color: #0a0f0a;
            font-family: 'Orbitron', monospace;
            box-shadow: 0 0 15px rgba(0,255,65,0.6);
        }
    </style>
</head>
<body class="radar-grid" style="background-color: #0a0f0a;">
    <!-- Header -->
    <header class="gradient-bg py-16 relative z-10">
        <div class="container mx-auto px-6 text-center relative z-20">
            <div class="mb-6">
                <svg class="w-16 h-16 mx-auto mb-4 text-green-400" fill="currentColor" viewBox="0 0 20 20" style="filter: drop-shadow(0 0 10px rgba(0,255,65,0.8));">
                    <path fill-rule="evenodd" d="M2.166 4.999A11.954 11.954 0 0010 1.944 11.954 11.954 0 0017.834 5c.11.65.166 1.32.166 2.001 0 5.225-3.34 9.67-8 11.317C5.34 16.67 2 12.225 2 7c0-.682.057-1.35.166-2.001zm11.541 3.708a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                </svg>
            </div>
            <h1 class="text-4xl md:text-5xl font-bold mb-4 military-text" style="color: #00ff41;">社區心理防衛與內部穩定指引</h1>
            <p class="text-xl max-w-3xl mx-auto" style="color: #88ff88;">建立堅實的心理防線，維護社區安全與團結</p>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-12">
        
        <!-- Section 1: 心理防衛三部曲 -->
        <section class="mb-16">
            <div class="section-card bg-white rounded-xl shadow-lg p-8">
                <h2 class="text-3xl font-bold mb-8 flex items-center military-text" style="color: #00ff41;">
                    <span class="section-number w-10 h-10 rounded-full flex items-center justify-center mr-4 text-xl">一</span>
                    建立心理防衛三部曲
                    <span class="text-sm ml-3" style="color: #88ff88;">（劉文）</span>
                </h2>
                
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="p-6 rounded-lg border-l-4 border-red-500" style="background: rgba(255,68,68,0.1); border-color: #ff4444;">
                        <div class="flex items-center mb-4">
                            <div class="step-number">1</div>
                            <h3 class="text-xl font-semibold" style="color: #ff6666;">風險感知</h3>
                        </div>
                        <p class="text-sm mb-2 font-medium military-text" style="color: #ff8888;">Risk Perception</p>
                        <ul class="space-y-2" style="color: #cccccc;">
                            <li>• 加強對政治與地緣風險的理解</li>
                            <li>• 建立資訊識讀能力，辨別謠言與假訊息</li>
                        </ul>
                    </div>
                    
                    <div class="p-6 rounded-lg border-l-4" style="background: rgba(0,255,65,0.1); border-color: #00ff41;">
                        <div class="flex items-center mb-4">
                            <div class="step-number">2</div>
                            <h3 class="text-xl font-semibold" style="color: #00ff41;">國家認同</h3>
                        </div>
                        <p class="text-sm mb-2 font-medium military-text" style="color: #88ff88;">National Identity</p>
                        <ul class="space-y-2" style="color: #cccccc;">
                            <li>• 強化敵我辨識，理解誰是真正的威脅</li>
                            <li>• 建立對社會共同體的信念與責任感</li>
                        </ul>
                    </div>
                    
                    <div class="p-6 rounded-lg border-l-4" style="background: rgba(0,255,255,0.1); border-color: #00ffff;">
                        <div class="flex items-center mb-4">
                            <div class="step-number">3</div>
                            <h3 class="text-xl font-semibold" style="color: #00ffff;">自我效能</h3>
                        </div>
                        <p class="text-sm mb-2 font-medium military-text" style="color: #88ffff;">Self-Efficacy</p>
                        <ul class="space-y-2" style="color: #cccccc;">
                            <li>• 培養個人與社區的韌性</li>
                            <li>• 強化「我有能力保護自己與社區」的信念</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 2: 認知戰四階段警報 -->
        <section class="mb-16">
            <div class="section-card bg-white rounded-xl shadow-lg p-8">
                <h2 class="text-3xl font-bold mb-8 flex items-center military-text" style="color: #00ff41;">
                    <span class="section-number w-10 h-10 rounded-full flex items-center justify-center mr-4 text-xl">二</span>
                    認知戰四階段警報
                    <span class="text-sm ml-3" style="color: #88ff88;">（Yuri Bezmenov 框架對照台灣）</span>
                </h2>
                
                <div class="space-y-6">
                    <div class="border-l-4 p-6 rounded-r-lg" style="background: rgba(255,255,0,0.1); border-color: #ffff00;">
                        <div class="phase-indicator">階段一</div>
                        <h3 class="text-xl font-semibold mb-3 military-text" style="color: #ffff00;">失去士氣 Demoralization</h3>
                        <ul class="space-y-1" style="color: #cccccc;">
                            <li>• 社群短影音、影劇文化滲透，加速價值觀被同化</li>
                            <li>• 改變一代人思想，可能僅需一個總統任期</li>
                        </ul>
                    </div>
                    
                    <div class="border-l-4 p-6 rounded-r-lg" style="background: rgba(255,165,0,0.1); border-color: #ffa500;">
                        <div class="phase-indicator">階段二</div>
                        <h3 class="text-xl font-semibold mb-3 military-text" style="color: #ffa500;">解裂社會 Destabilization</h3>
                        <ul class="space-y-1" style="color: #cccccc;">
                            <li>• 操縱言論自由，放大政府失誤、製造仇恨政治</li>
                            <li>• 特定政治人物的口號式言論，削弱國民信任感</li>
                        </ul>
                    </div>
                    
                    <div class="border-l-4 p-6 rounded-r-lg" style="background: rgba(255,68,68,0.1); border-color: #ff4444;">
                        <div class="phase-indicator">階段三</div>
                        <h3 class="text-xl font-semibold mb-3 military-text" style="color: #ff4444;">製造危機 Crisis</h3>
                        <ul class="space-y-1" style="color: #cccccc;">
                            <li>• 短時間內摧毀制度與秩序</li>
                            <li>• 例：國會程序濫用、國防預算封殺、法規隨意扭曲</li>
                        </ul>
                    </div>
                    
                    <div class="border-l-4 p-6 rounded-r-lg" style="background: rgba(128,128,128,0.1); border-color: #808080;">
                        <div class="phase-indicator">階段四</div>
                        <h3 class="text-xl font-semibold mb-3 military-text" style="color: #808080;">常態化 Normalization</h3>
                        <ul class="space-y-1" style="color: #cccccc;">
                            <li>• 將不正常變成「新常態」，讓人習以為常</li>
                            <li>• 例：中國持續軍事威脅、灰色地帶活動、第五縱隊滲透</li>
                        </ul>
                    </div>
                </div>
                
                <div class="mt-6 rounded-lg p-4 warning-pulse">
                    <div class="flex items-center">
                        <span class="text-2xl mr-3" style="filter: drop-shadow(0 0 10px rgba(255,68,68,0.8));">⚠️</span>
                        <p class="font-semibold military-text" style="color: #ff4444;">警語：真正的危險是「麻痺」與「習慣」。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 3: 個資保護與敵我辨識 -->
        <section class="mb-16">
            <div class="section-card bg-white rounded-xl shadow-lg p-8">
                <h2 class="text-3xl font-bold mb-8 flex items-center military-text" style="color: #00ff41;">
                    <span class="section-number w-10 h-10 rounded-full flex items-center justify-center mr-4 text-xl">三</span>
                    個資保護與敵我辨識
                </h2>
                
                <div class="grid md:grid-cols-3 gap-6">
                    <div class="p-6 rounded-lg border border-purple-500" style="background: rgba(128,0,128,0.1);">
                        <h3 class="text-lg font-semibold mb-3 military-text" style="color: #ff00ff;">🔒 避免個資外流</h3>
                        <p style="color: #cccccc;">不在陌生群組透露真名、住址、工作地</p>
                    </div>
                    
                    <div class="p-6 rounded-lg border border-cyan-500" style="background: rgba(0,255,255,0.1);">
                        <h3 class="text-lg font-semibold mb-3 military-text" style="color: #00ffff;">🏷️ 律定辨識系統</h3>
                        <p style="color: #cccccc;">使用臂章或特定顏色膠帶，定期更新以防敵方仿冒</p>
                    </div>
                    
                    <div class="p-6 rounded-lg border border-yellow-500" style="background: rgba(255,255,0,0.1);">
                        <h3 class="text-lg font-semibold mb-3 military-text" style="color: #ffff00;">🛡️ 風險管控</h3>
                        <p style="color: #cccccc;">若資料已外洩，需做好自我安全防護</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 4: 信任與團結的維護 -->
        <section class="mb-16">
            <div class="section-card bg-white rounded-xl shadow-lg p-8">
                <h2 class="text-3xl font-bold mb-8 flex items-center military-text" style="color: #00ff41;">
                    <span class="section-number w-10 h-10 rounded-full flex items-center justify-center mr-4 text-xl">四</span>
                    信任與團結的維護
                </h2>
                
                <div class="space-y-6">
                    <div class="flex items-start">
                        <div class="p-3 rounded-full mr-4 mt-1" style="background: rgba(0,255,65,0.2);">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" style="color: #00ff41;">
                                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold mb-2 military-text" style="color: #00ff41;">避免內部互相懷疑過度</h3>
                            <p style="color: #cccccc;">在合理懷疑基礎上，避免造成不必要的猜忌</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="p-3 rounded-full mr-4 mt-1" style="background: rgba(0,255,255,0.2);">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" style="color: #00ffff;">
                                <path d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3z"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold mb-2 military-text" style="color: #00ffff;">鼓勵正向合作</h3>
                            <p style="color: #cccccc;">持續溝通與協作，維持團體凝聚力</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="p-3 rounded-full mr-4 mt-1" style="background: rgba(255,255,0,0.2);">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" style="color: #ffff00;">
                                <path fill-rule="evenodd" d="M4 4a2 2 0 00-2 2v8a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2H4zm3 5a1 1 0 011-1h4a1 1 0 110 2H8a1 1 0 01-1-1zm0 3a1 1 0 011-1h4a1 1 0 110 2H8a1 1 0 01-1-1z" clip-rule="evenodd"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold mb-2 military-text" style="color: #ffff00;">維護社區運作</h3>
                            <p style="color: #cccccc;">即使有滲透與挑釁，照常運作，不受干擾</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 5: 第五縱隊影響與因應 -->
        <section class="mb-16">
            <div class="section-card bg-white rounded-xl shadow-lg p-8">
                <h2 class="text-3xl font-bold mb-8 flex items-center military-text" style="color: #00ff41;">
                    <span class="section-number w-10 h-10 rounded-full flex items-center justify-center mr-4 text-xl">五</span>
                    五縱（第五縱隊）可能影響與因應
                </h2>
                
                <div class="mb-6">
                    <h3 class="text-xl font-semibold mb-3 military-text" style="color: #00ff41;">平時潛伏</h3>
                    <p class="p-4 rounded-lg border border-gray-600" style="color: #cccccc; background: rgba(128,128,128,0.1);">難以察覺，高風險時以行為判斷</p>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold mb-4 military-text" style="color: #00ff41;">戰時危害與因應</h3>
                    <div class="grid md:grid-cols-2 gap-6">
                        <div class="border p-4 rounded-lg" style="background: rgba(255,68,68,0.1); border-color: #ff4444;">
                            <h4 class="font-semibold mb-2 military-text" style="color: #ff6666;">散播恐慌謠言</h4>
                            <p class="text-sm" style="color: #cccccc;">→ 不轉傳、協助澄清</p>
                        </div>
                        
                        <div class="border p-4 rounded-lg" style="background: rgba(255,165,0,0.1); border-color: #ffa500;">
                            <h4 class="font-semibold mb-2 military-text" style="color: #ffa500;">偽裝平民帶動暴動</h4>
                            <p class="text-sm" style="color: #cccccc;">→ 協助維持社區秩序</p>
                        </div>
                        
                        <div class="border p-4 rounded-lg" style="background: rgba(255,255,0,0.1); border-color: #ffff00;">
                            <h4 class="font-semibold mb-2 military-text" style="color: #ffff00;">故意誤導避難</h4>
                            <p class="text-sm" style="color: #cccccc;">→ 預先熟悉社區避難路線，不盲從人群</p>
                        </div>
                        
                        <div class="border p-4 rounded-lg" style="background: rgba(255,0,255,0.1); border-color: #ff00ff;">
                            <h4 class="font-semibold mb-2 military-text" style="color: #ff00ff;">製造內部猜忌與矛盾</h4>
                            <p class="text-sm" style="color: #cccccc;">→ 強調團結、跨族群合作</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 6: 三項具體建議 -->
        <section class="mb-16">
            <div class="section-card bg-white rounded-xl shadow-lg p-8">
                <h2 class="text-3xl font-bold mb-8 flex items-center military-text" style="color: #00ff41;">
                    <span class="section-number w-10 h-10 rounded-full flex items-center justify-center mr-4 text-xl">六</span>
                    三項具體建議
                    <span class="text-sm ml-3" style="color: #88ff88;">（劉玉皙教授）</span>
                </h2>
                
                <div class="space-y-4">
                    <div class="flex items-start p-4 rounded-lg border" style="background: rgba(0,255,255,0.1); border-color: #00ffff;">
                        <span class="w-8 h-8 rounded-full flex items-center justify-center mr-4 text-sm font-bold flex-shrink-0 military-text" style="background: #00ffff; color: #0a0f0a;">1</span>
                        <p style="color: #cccccc;">避免捲入極端立場討論，降低情緒操控風險</p>
                    </div>
                    
                    <div class="flex items-start p-4 rounded-lg border" style="background: rgba(0,255,255,0.1); border-color: #00ffff;">
                        <span class="w-8 h-8 rounded-full flex items-center justify-center mr-4 text-sm font-bold flex-shrink-0 military-text" style="background: #00ffff; color: #0a0f0a;">2</span>
                        <p style="color: #cccccc;">區分資訊層次：內圈機密不落字、不外傳</p>
                    </div>
                    
                    <div class="flex items-start p-4 rounded-lg border" style="background: rgba(0,255,255,0.1); border-color: #00ffff;">
                        <span class="w-8 h-8 rounded-full flex items-center justify-center mr-4 text-sm font-bold flex-shrink-0 military-text" style="background: #00ffff; color: #0a0f0a;">3</span>
                        <p style="color: #cccccc;">保持組織運作持續推進，不因懷疑而停擺</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Core Message -->
        <section class="mb-16">
            <div class="rounded-xl p-8 text-center border-2" style="background: linear-gradient(135deg, rgba(0,255,65,0.1) 0%, rgba(0,255,255,0.1) 100%); border-color: #00ff41;">
                <h2 class="text-3xl font-bold mb-6 flex items-center justify-center military-text" style="color: #00ff41;">
                    🎯 核心訊息
                </h2>
                
                <div class="grid md:grid-cols-3 gap-6 text-lg">
                    <div class="p-6 rounded-lg border" style="background: rgba(0,255,65,0.2); border-color: #00ff41;">
                        <h3 class="font-bold mb-2 military-text" style="color: #00ff41;">心理防衛</h3>
                        <p style="color: #cccccc;">是第一道防線</p>
                    </div>
                    
                    <div class="p-6 rounded-lg border" style="background: rgba(0,255,255,0.2); border-color: #00ffff;">
                        <h3 class="font-bold mb-2 military-text" style="color: #00ffff;">信任與團結</h3>
                        <p style="color: #cccccc;">是社區最強大的盾牌</p>
                    </div>
                    
                    <div class="p-6 rounded-lg border" style="background: rgba(255,255,0,0.2); border-color: #ffff00;">
                        <h3 class="font-bold mb-2 military-text" style="color: #ffff00;">不麻痺、不習慣</h3>
                        <p style="color: #cccccc;">才能守住台灣的自由與安全</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="py-8 border-t-2" style="background: rgba(10,15,10,0.9); border-color: #00ff41;">
        <div class="container mx-auto px-6 text-center">
            <p class="military-text" style="color: #88ff88;">© 2024 社區心理防衛指引 - 守護台灣，從心理防線開始</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for better user experience
        document.addEventListener('DOMContentLoaded', function() {
            // Add fade-in animation to sections
            const sections = document.querySelectorAll('.section-card');
            
            const observerOptions = {
                threshold: 0.1,
                rootMargin: '0px 0px -50px 0px'
            };
            
            const observer = new IntersectionObserver(function(entries) {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, observerOptions);
            
            sections.forEach(section => {
                section.style.opacity = '0';
                section.style.transform = 'translateY(20px)';
                section.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
                observer.observe(section);
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'97510b0672360730',t:'MTc1NjE4NzMzNy4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
