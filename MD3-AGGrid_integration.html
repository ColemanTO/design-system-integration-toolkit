<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design System Integration: Visual Mapping Methodology</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            overflow: hidden;
        }

        .presentation {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .slide {
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.1);
            width: 90vw;
            max-width: 1200px;
            height: 80vh;
            padding: 60px;
            display: none;
            flex-direction: column;
            justify-content: center;
            position: relative;
            overflow-y: auto;
        }

        .slide.active {
            display: flex;
        }

        .slide h1 {
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 2rem;
            background: linear-gradient(135deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            line-height: 1.2;
        }

        .slide h2 {
            font-size: 2.5rem;
            font-weight: 600;
            margin-bottom: 1.5rem;
            color: #2c3e50;
        }

        .slide h3 {
            font-size: 1.8rem;
            font-weight: 600;
            margin-bottom: 1rem;
            color: #34495e;
        }

        .slide p {
            font-size: 1.3rem;
            line-height: 1.6;
            margin-bottom: 1.5rem;
            color: #555;
        }

        .slide ul {
            font-size: 1.2rem;
            line-height: 1.8;
            margin-left: 2rem;
            margin-bottom: 1.5rem;
        }

        .slide li {
            margin-bottom: 0.8rem;
            color: #555;
        }

        .subtitle {
            font-size: 1.5rem;
            color: #666;
            font-weight: 400;
            margin-top: -1rem;
            margin-bottom: 3rem;
        }

        .author {
            font-size: 1.2rem;
            color: #888;
            margin-top: 2rem;
        }

        .navigation {
            position: fixed;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 15px;
            z-index: 1000;
        }

        .nav-btn {
            background: rgba(255,255,255,0.9);
            border: none;
            border-radius: 50px;
            padding: 15px 25px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .nav-btn:hover {
            background: white;
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }

        .slide-counter {
            position: absolute;
            top: 30px;
            right: 30px;
            background: rgba(102, 126, 234, 0.1);
            padding: 10px 20px;
            border-radius: 25px;
            font-weight: 600;
            color: #667eea;
        }

        .problem-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
            margin: 2rem 0;
        }

        .problem-card {
            background: #f8f9fa;
            padding: 2rem;
            border-radius: 15px;
            border-left: 5px solid #e74c3c;
        }

        .solution-card {
            background: #f8f9fa;
            padding: 2rem;
            border-radius: 15px;
            border-left: 5px solid #27ae60;
        }

        .methodology-steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .step-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
            transform: translateY(0);
            transition: transform 0.3s ease;
        }

        .step-card:hover {
            transform: translateY(-5px);
        }

        .step-number {
            font-size: 2rem;
            font-weight: bold;
            margin-bottom: 1rem;
            opacity: 0.8;
        }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .benefit-card {
            background: #f8f9fa;
            padding: 2rem;
            border-radius: 15px;
            border-top: 4px solid #667eea;
            text-align: center;
        }

        .emoji {
            font-size: 3rem;
            margin-bottom: 1rem;
            display: block;
        }

        .code-block {
            background: #2c3e50;
            color: #ecf0f1;
            padding: 1.5rem;
            border-radius: 10px;
            font-family: 'Courier New', monospace;
            margin: 1rem 0;
            overflow-x: auto;
        }

        .highlight {
            background: linear-gradient(120deg, #a8edea 0%, #fed6e3 100%);
            padding: 0.2rem 0.5rem;
            border-radius: 5px;
            font-weight: 600;
        }

        .call-to-action {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 3rem;
            border-radius: 20px;
            text-align: center;
            margin-top: 2rem;
        }

        .diagram-preview {
            background: #f8f9fa;
            padding: 2rem;
            border-radius: 15px;
            margin: 2rem 0;
            text-align: center;
            border: 2px dashed #667eea;
        }

        @media (max-width: 768px) {
            .slide {
                padding: 30px;
                width: 95vw;
                height: 85vh;
            }
            
            .slide h1 {
                font-size: 2.5rem;
            }
            
            .problem-grid {
                grid-template-columns: 1fr;
                gap: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="presentation">
        <!-- Slide 1: Title -->
        <div class="slide active">
            <div class="slide-counter">1 / 12</div>
            <h1>Beyond Documentation</h1>
            <p class="subtitle">Visual Mapping for Design System Integration</p>
            <p style="font-size: 1.4rem; margin: 3rem 0;">How we created the "Swagger docs" for design systems</p>
            <div class="author">Your Name • Your Company • Conference/Meetup 2025</div>
        </div>

        <!-- Slide 2: The Problem -->
        <div class="slide">
            <div class="slide-counter">2 / 12</div>
            <h2>The Integration Problem</h2>
            <div class="problem-grid">
                <div class="problem-card">
                    <h3>😤 Current Reality</h3>
                    <ul>
                        <li>Design systems exist in isolation</li>
                        <li>Component libraries have their own theming</li>
                        <li>Teams spend weeks mapping tokens manually</li>
                        <li>Inconsistent implementations across projects</li>
                    </ul>
                </div>
                <div class="problem-card">
                    <h3>💸 The Cost</h3>
                    <ul>
                        <li>Weeks of developer time per integration</li>
                        <li>Design-dev handoff confusion</li>
                        <li>Maintenance nightmare</li>
                        <li>Brand inconsistency in data-heavy UIs</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- Slide 3: Real Example -->
        <div class="slide">
            <div class="slide-counter">3 / 12</div>
            <h2>Real Example: Material Design 3 + AG Grid</h2>
            <div class="diagram-preview">
                <h3>🎯 The Challenge</h3>
                <p>How do you map 50+ Material Design 3 color tokens to 100+ AG Grid CSS variables?</p>
                <div class="code-block">
/* Material Design 3 */
--md-sys-color-primary: #6750a4;
--md-sys-color-primary-container: #eaddff;

/* AG Grid */
--ag-foreground-color: ???;
--ag-selected-row-background-color: ???;
                </div>
                <p><strong>Before:</strong> Weeks of trial and error<br>
                <strong>After:</strong> Visual integration map</p>
            </div>
        </div>

        <!-- Slide 4: The Solution -->
        <div class="slide">
            <div class="slide-counter">4 / 12</div>
            <h2>The Solution: Visual Integration Maps</h2>
            <div class="solution-card">
                <h3>🗺️ Think "API Documentation" for Design Systems</h3>
                <p>Just like Swagger docs show how APIs connect, we need visual maps showing how design systems integrate.</p>
            </div>
            <div class="methodology-steps">
                <div class="step-card">
                    <div class="step-number">1</div>
                    <h3>Map</h3>
                    <p>Identify token relationships</p>
                </div>
                <div class="step-card">
                    <div class="step-number">2</div>
                    <h3>Visualize</h3>
                    <p>Create clear diagrams</p>
                </div>
                <div class="step-card">
                    <div class="step-number">3</div>
                    <h3>Document</h3>
                    <p>Make it accessible</p>
                </div>
                <div class="step-card">
                    <div class="step-number">4</div>
                    <h3>Implement</h3>
                    <p>Use in Storybook & docs</p>
                </div>
            </div>
        </div>

        <!-- Slide 5: Our Approach -->
        <div class="slide">
            <div class="slide-counter">5 / 12</div>
            <h2>Our Visual Mapping Approach</h2>
            <h3>🎨 Three Focused Diagrams</h3>
            <div class="benefits-grid">
                <div class="benefit-card">
                    <span class="emoji">🎨</span>
                    <h3>Color Relationships</h3>
                    <p>MD3 color tokens → AG Grid color variables</p>
                </div>
                <div class="benefit-card">
                    <span class="emoji">📝</span>
                    <h3>Typography Mapping</h3>
                    <p>MD3 typescale → AG Grid font variables</p>
                </div>
                <div class="benefit-card">
                    <span class="emoji">📏</span>
                    <h3>Spacing Integration</h3>
                    <p>MD3 spacing tokens → AG Grid layout variables</p>
                </div>
            </div>
            <p><strong>Tool:</strong> Mermaid diagrams (works in DrawIO, GitHub, Confluence)</p>
        </div>

        <!-- Slide 6: Diagram Types -->
        <div class="slide">
            <div class="slide-counter">6 / 12</div>
            <h2>Three Types of Mappings</h2>
            <div class="problem-grid">
                <div style="background: #e8f5e8; padding: 2rem; border-radius: 15px; border-left: 5px solid #27ae60;">
                    <h3>✅ Direct Mappings</h3>
                    <p>1:1 token relationships</p>
                    <div class="code-block" style="font-size: 0.9rem;">
--md-sys-color-surface → --ag-background-color
                    </div>
                </div>
                <div style="background: #e3f2fd; padding: 2rem; border-radius: 15px; border-left: 5px solid #2196f3;">
                    <h3>🎯 Semantic Mappings</h3>
                    <p>Purpose-based relationships</p>
                    <div class="code-block" style="font-size: 0.9rem;">
--md-sys-color-primary-container → --ag-selected-row-background-color
                    </div>
                </div>
            </div>
            <div style="background: #fff3e0; padding: 2rem; border-radius: 15px; border-left: 5px solid #ff9800; margin-top: 2rem;">
                <h3>🧮 Calculated Mappings</h3>
                <p>Requires mathematical transformation</p>
                <div class="code-block" style="font-size: 0.9rem;">
--md-sys-spacing-3 → calc(var(--md-sys-spacing-3) * 4) → --ag-header-height
                </div>
            </div>
        </div>

        <!-- Slide 7: Benefits -->
        <div class="slide">
            <div class="slide-counter">7 / 12</div>
            <h2>The Impact</h2>
            <div class="benefits-grid">
                <div class="benefit-card">
                    <span class="emoji">⚡</span>
                    <h3>Speed</h3>
                    <p><span class="highlight">Weeks → Hours</span><br>Integration time</p>
                </div>
                <div class="benefit-card">
                    <span class="emoji">🤝</span>
                    <h3>Collaboration</h3>
                    <p>Designers & developers speak the same language</p>
                </div>
                <div class="benefit-card">
                    <span class="emoji">📚</span>
                    <h3>Documentation</h3>
                    <p>Living docs in Confluence & Storybook</p>
                </div>
                <div class="benefit-card">
                    <span class="emoji">🎯</span>
                    <h3>Consistency</h3>
                    <p>Same approach across all integrations</p>
                </div>
                <div class="benefit-card">
                    <span class="emoji">🔄</span>
                    <h3>Maintainable</h3>
                    <p>Easy updates as systems evolve</p>
                </div>
                <div class="benefit-card">
                    <span class="emoji">📈</span>
                    <h3>Scalable</h3>
                    <p>Template for future integrations</p>
                </div>
            </div>
        </div>

        <!-- Slide 8: Implementation -->
        <div class="slide">
            <div class="slide-counter">8 / 12</div>
            <h2>How We Use These</h2>
            <h3>🛠️ Practical Implementation</h3>
            <ul style="font-size: 1.4rem; line-height: 2;">
                <li><strong>Confluence:</strong> Architecture documentation for teams</li>
                <li><strong>Storybook:</strong> Live examples alongside diagrams</li>
                <li><strong>Code Reviews:</strong> Reference for consistent implementations</li>
                <li><strong>Design Handoffs:</strong> Clear specifications for developers</li>
                <li><strong>Onboarding:</strong> New team members get up to speed fast</li>
            </ul>
            <div class="diagram-preview">
                <p><strong>Real Result:</strong> New developer integrated AG Grid with our design system in <span class="highlight">2 hours</span> instead of 2 weeks</p>
            </div>
        </div>

        <!-- Slide 9: Tools & Process -->
        <div class="slide">
            <div class="slide-counter">9 / 12</div>
            <h2>Tools & Process</h2>
            <div class="methodology-steps">
                <div class="step-card">
                    <h3>📊 Mermaid</h3>
                    <p>Diagram creation<br>(works everywhere)</p>
                </div>
                <div class="step-card">
                    <h3>🎨 DrawIO</h3>
                    <p>Diagram refinement<br>& collaboration</p>
                </div>
                <div class="step-card">
                    <h3>📚 Confluence</h3>
                    <p>Team documentation<br>& architecture</p>
                </div>
                <div class="step-card">
                    <h3>🔧 Storybook</h3>
                    <p>Live examples<br>& validation</p>
                </div>
            </div>
            <div class="code-block">
# Our Process
1. Research both systems' token/variable structure
2. Identify mapping relationships (direct, semantic, calculated)
3. Create Mermaid diagram with clear categorization
4. Test mappings in Storybook components
5. Document in Confluence with implementation examples
            </div>
        </div>

        <!-- Slide 10: Beyond Our Example -->
        <div class="slide">
            <div class="slide-counter">10 / 12</div>
            <h2>Beyond Material Design 3 + AG Grid</h2>
            <h3>🌍 This Works for Any Integration</h3>
            <div class="problem-grid">
                <div class="solution-card">
                    <h3>Popular Combinations</h3>
                    <ul>
                        <li>Ant Design + React Table</li>
                        <li>Chakra UI + AG Grid</li>
                        <li>Carbon + DataTables</li>
                        <li>Fluent + DevExpress</li>
                    </ul>
                </div>
                <div class="solution-card">
                    <h3>Beyond Data Tables</h3>
                    <ul>
                        <li>Design System + Chart Libraries</li>
                        <li>Design System + Map Components</li>
                        <li>Design System + Rich Text Editors</li>
                        <li>Any complex component integration</li>
                    </ul>
                </div>
            </div>
            <p style="margin-top: 2rem; font-size: 1.4rem; text-align: center;">
                <strong>The methodology is the same:</strong> Map → Visualize → Document → Implement
            </p>
        </div>

        <!-- Slide 11: Open Source -->
        <div class="slide">
            <div class="slide-counter">11 / 12</div>
            <h2>We're Open Sourcing This!</h2>
            <div class="call-to-action">
                <h3>🎁 Coming Soon: Design System Integration Toolkit</h3>
                <ul style="text-align: left; margin: 2rem 0; font-size: 1.3rem;">
                    <li>✅ Complete Mermaid diagram templates</li>
                    <li>✅ Step-by-step methodology guide</li>
                    <li>✅ Storybook integration examples</li>
                    <li>✅ Confluence documentation templates</li>
                    <li>✅ Multiple design system examples</li>
                </ul>
                <p style="font-size: 1.4rem; margin-top: 2rem;">
                    <strong>GitHub:</strong> github.com/[your-username]/design-system-integration-toolkit
                </p>
            </div>
        </div>

        <!-- Slide 12: Call to Action -->
        <div class="slide">
            <div class="slide-counter">12 / 12</div>
            <h1>Let's Connect!</h1>
            <div class="benefits-grid">
                <div class="benefit-card">
                    <span class="emoji">💬</span>
                    <h3>Questions?</h3>
                    <p>Ask me anything about visual integration mapping</p>
                </div>
                <div class="benefit-card">
                    <span class="emoji">🤝</span>
                    <h3>Collaborate</h3>
                    <p>Let's build more integration examples together</p>
                </div>
                <div class="benefit-card">
                    <span class="emoji">📧</span>
                    <h3>Contact</h3>
                    <p>your.email@company.com<br>@yourhandle</p>
                </div>
            </div>
            <div class="call-to-action">
                <h3>Try This Approach!</h3>
                <p>Pick any design system + component library combo and create your first visual integration map</p>
            </div>
        </div>
    </div>

    <div class="navigation">
        <button class="nav-btn" onclick="previousSlide()">← Previous</button>
        <button class="nav-btn" onclick="nextSlide()">Next →</button>
    </div>

    <script>
        let currentSlide = 0;
        const slides = document.querySelectorAll('.slide');
        const totalSlides = slides.length;

        function showSlide(n) {
            slides.forEach(slide => slide.classList.remove('active'));
            slides[n].classList.add('active');
        }

        function nextSlide() {
            currentSlide = (currentSlide + 1) % totalSlides;
            showSlide(currentSlide);
        }

        function previousSlide() {
            currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
            showSlide(currentSlide);
        }

        // Keyboard navigation
        document.addEventListener('keydown', function(e) {
            if (e.key === 'ArrowRight' || e.key === ' ') {
                nextSlide();
            } else if (e.key === 'ArrowLeft') {
                previousSlide();
            }
        });

        // Auto-advance slides every 30 seconds (optional)
        // setInterval(nextSlide, 30000);
    </script>
</body>
</html>