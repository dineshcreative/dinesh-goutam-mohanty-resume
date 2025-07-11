<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dinesh Goutam Mohanty - Digital Marketing Manager</title>
    <meta name="description" content="Resume website for Dinesh Goutam Mohanty, Digital Marketing Manager.">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600;700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --color-primary: #3498db;
            --color-secondary: #2c3e50;
            --color-bg: #f8f8f8;
            --color-white: #fff;
            --color-accent: #e67e22;
            --color-muted: #555;
            --color-shadow: rgba(44,62,80,0.10);
        }
        body {
            font-family: 'Open Sans', Arial, sans-serif;
            background: var(--color-bg);
            color: var(--color-secondary);
            margin: 0;
            padding: 0;
        }
        header {
            background: linear-gradient(90deg, var(--color-primary) 60%, var(--color-secondary) 100%);
            color: var(--color-white);
            padding: 50px 0 30px 0;
            text-align: center;
            position: relative;
        }
        header h1 {
            font-family: 'Montserrat', 'Open Sans', sans-serif;
            font-size: 2.8em;
            margin: 0;
            letter-spacing: 1px;
        }
        header h2 {
            font-size: 1.2em;
            margin: 15px 0 0 0;
            font-weight: 400;
            letter-spacing: 0.5px;
        }
        .contact-info {
            margin: 20px 0 0 0;
            font-size: 1.1em;
        }
        .contact-info a {
            color: var(--color-accent);
            text-decoration: none;
            margin: 0 8px;
            transition: color 0.2s;
        }
        .contact-info a:hover {
            color: var(--color-white);
            text-decoration: underline;
        }
        main {
            max-width: 1000px;
            margin: -40px auto 0 auto;
            background: var(--color-white);
            border-radius: 16px;
            box-shadow: 0 6px 32px var(--color-shadow);
            padding: 40px 36px 32px 36px;
        }
        section {
            margin-bottom: 36px;
        }
        h3.section-title {
            color: var(--color-primary);
            font-family: 'Montserrat', sans-serif;
            font-size: 1.4em;
            border-left: 5px solid var(--color-primary);
            padding-left: 14px;
            margin-bottom: 20px;
            margin-top: 0;
            letter-spacing: 0.5px;
        }
        p, ul, li {
            font-size: 1.08em;
            line-height: 1.7;
        }
        ul {
            padding: 0;
            list-style-type: none;
        }
        ul li {
            position: relative;
            margin-bottom: 10px;
            padding-left: 22px;
        }
        ul li:before {
            content: '•';
            position: absolute;
            left: 0;
            color: var(--color-primary);
            font-size: 1.2em;
            top: 2px;
        }
        .experience-entry {
            margin-bottom: 28px;
            border-left: 3px solid var(--color-primary);
            padding-left: 16px;
        }
        .experience-entry h4 {
            margin: 0 0 4px 0;
            color: var(--color-secondary);
            font-weight: 600;
            font-size: 1.13em;
        }
        .experience-entry .date-location {
            font-size: 0.98em;
            color: var(--color-muted);
            font-style: italic;
            margin-bottom: 8px;
        }
        .skills-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 26px;
        }
        .skill-card {
            flex: 1 1 260px;
            min-width: 220px;
            background: #f4fafe;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(52,152,219,0.07);
            padding: 20px 18px 15px 18px;
            margin-bottom: 10px;
            transition: box-shadow 0.2s;
        }
        .skill-card:hover {
            box-shadow: 0 8px 24px rgba(52,152,219,0.12);
        }
        .skill-card h5 {
            color: var(--color-primary);
            margin: 0 0 12px 0;
            font-size: 1.08em;
            font-family: 'Montserrat', sans-serif;
        }
        .achievements ul li:before, .education ul li:before, .languages ul li:before {
            content: '★';
            color: var(--color-accent);
            font-size: 1.03em;
        }
        .languages {
            display: flex;
            flex-wrap: wrap;
            gap: 38px;
        }
        .languages ul {
            min-width: 220px;
        }
        footer {
            background: var(--color-secondary);
            color: var(--color-white);
            text-align: center;
            font-size: 1em;
            padding: 20px 0 10px 0;
            margin-top: 35px;
            border-radius: 0 0 12px 12px;
        }
        /* Responsive */
        @media (max-width: 900px) {
            main {
                padding: 18px 5vw 22px 5vw;
            }
            .skills-grid {
                flex-direction: column;
                gap: 12px;
            }
            .languages {
                flex-direction: column;
                gap: 10px;
            }
        }
        @media (max-width: 600px) {
            header {
                padding: 34px 0 16px 0;
            }
            main {
                margin: -24px 0 0 0;
                border-radius: 0;
                padding: 14px 2vw 18px 2vw;
            }
            .experience-entry {
                padding-left: 7px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Dinesh Goutam Mohanty</h1>
        <h2>Digital Marketing Manager</h2>
        <div class="contact-info">
            <a href="mailto:dineshgoutamofficial@gmail.com" title="Email">dineshgoutamofficial@gmail.com</a> |
            <span title="Phone">+91 9777393776</span> |
            <span>Bengaluru, India</span> |
            <a href="https://linkedin.com/dinesh-goutam-mohanty/" target="_blank" rel="noopener">LinkedIn</a>
        </div>
    </header>
    <main>
        <section>
            <h3 class="section-title">Professional Summary</h3>
            <p>
                Performance-focused Digital Marketing Manager with 3+ years’ experience in Meta and Google Ads, content direction, and full-funnel campaigns.
                Proven ability to scale campaigns across Edtech, Real Estate, E-commerce, F&B, Healthcare, and Travel, achieving ROAS up to <strong>900%</strong>.
                Skilled in team leadership, ad strategy, and driving site visits, leads, and revenue through data-backed marketing. Managed monthly budgets up to <strong>INR 3 Lakhs/client</strong> and produced high-converting creatives.
            </p>
        </section>
        <section>
            <h3 class="section-title">Professional Experience</h3>
            <div class="experience-entry">
                <h4>Digital Marketing Manager, Highbizz Solution Pvt Ltd</h4>
                <div class="date-location">07/2024–Present &mdash; Bengaluru</div>
                <ul>
                    <li>Managed 15+ clients with a team of 5 across Edtech, Real Estate, F&B, E-commerce, and Healthcare.</li>
                    <li>Achieved ROAS benchmarks: Ed-tech (700%), E-commerce (400%), Healthcare (350%), Travel (90% booking rate).</li>
                    <li>Directed emotion-based creative campaigns; handled monthly budgets up to 3 Lakhs/client.</li>
                    <li>Built brand visibility via content calendars for Facebook, Instagram, LinkedIn.</li>
                    <li>Implemented advanced digital frameworks (SWOT, BCG, Ansoff) in marketing strategies.</li>
                </ul>
            </div>
            <div class="experience-entry">
                <h4>Freelance Digital Marketing Specialist, Blackeast Commercials (Remote)</h4>
                <div class="date-location">04/2024–06/2024</div>
                <ul>
                    <li>Managed social campaigns and ideation for international clients (Australia, Germany).</li>
                    <li>Delivered creative content strategies, improving brand recall and engagement.</li>
                </ul>
            </div>
            <div class="experience-entry">
                <h4>Growth Marketing Manager (Promoted from Lead &amp; Associate), Edtech Startup</h4>
                <div class="date-location">08/2022–03/2024 &mdash; Bhubaneswar</div>
                <ul>
                    <li>Managed Meta &amp; Google Ads with up to 900% ROAS on ₹90,000 monthly budget.</li>
                    <li>Handled 360° digital marketing: WhatsApp, email, social media, and community growth.</li>
                    <li>Secured partnerships with 3 major government colleges via personalized campaigns.</li>
                    <li>Tools used: Google Analytics, Meta Suite, Zoho Campaigns, Ubersuggest, Kylas CRM.</li>
                </ul>
            </div>
            <div class="experience-entry">
                <h4>Business Development Executive, Intellipaat</h4>
                <div class="date-location">08/2022–10/2022 &mdash; Bangalore</div>
                <ul>
                    <li>Drove lead generation and sales closures for online education programs.</li>
                </ul>
            </div>
        </section>
        <section>
            <h3 class="section-title">Education</h3>
            <ul class="education">
                <li><strong>Bachelor of Business Administration (Marketing):</strong> Birla Global University, Bhubaneswar (2019–2022)</li>
                <li><strong>12th (Commerce):</strong> Himali Boarding School, Kurseong (2017–2019)</li>
                <li><strong>10th (Science):</strong> Stewart School, Cuttack (2004–2016)</li>
            </ul>
        </section>
        <section>
            <h3 class="section-title">Key Skills</h3>
            <div class="skills-grid">
                <div class="skill-card">
                    <h5>Advertising &amp; Paid Media <span style="color:var(--color-muted);font-size:0.92em;">(Expert)</span></h5>
                    <ul>
                        <li>Meta Ads (Facebook, Instagram)</li>
                        <li>Google Ads (Search, Display, Video)</li>
                        <li>Amazon Ads</li>
                        <li>Budget Optimization</li>
                        <li>A/B Testing</li>
                        <li>Campaign Strategy</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h5>Analytics &amp; Tools <span style="color:var(--color-muted);font-size:0.92em;">(Proficient)</span></h5>
                    <ul>
                        <li>Google Analytics</li>
                        <li>Search Console</li>
                        <li>MS Clarity</li>
                        <li>Data Studio</li>
                        <li>Ubersuggest</li>
                        <li>Semrush</li>
                        <li>Google Tag Manager</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h5>Marketing Strategy &amp; CRM <span style="color:var(--color-muted);font-size:0.92em;">(Expert)</span></h5>
                    <ul>
                        <li>Email/WhatsApp Campaigns</li>
                        <li>Lead Funnels</li>
                        <li>Business Models (SWOT, BCG, Ansoff)</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h5>Content &amp; Social Media <span style="color:var(--color-muted);font-size:0.92em;">(Proficient)</span></h5>
                    <ul>
                        <li>Content Calendars</li>
                        <li>Copywriting</li>
                        <li>Creative Briefs</li>
                        <li>Emotion-based Storytelling</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h5>CRM &amp; Sales Tools <span style="color:var(--color-muted);font-size:0.92em;">(Proficient)</span></h5>
                    <ul>
                        <li>Zoho CRM</li>
                        <li>Kylas CRM</li>
                        <li>Cronberry</li>
                        <li>Privyr</li>
                        <li>Canva</li>
                        <li>PowerPoint</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h5>Community Management <span style="color:var(--color-muted);font-size:0.92em;">(Proficient)</span></h5>
                    <ul>
                        <li>Sales Enablement</li>
                    </ul>
                </div>
            </div>
        </section>
        <section>
            <h3 class="section-title">Key Achievements</h3>
            <div class="achievements">
                <ul>
                    <li>Delivered 700% ROAS for Edtech; 350% ROAS for Healthcare &amp; E-commerce.</li>
                    <li>Achieved 350% growth in store visits for a luxury furniture brand.</li>
                    <li>Generated 70–90% booking rates for travel &amp; tourism clients.</li>
                    <li>Secured 3 government college partnerships through customized outreach.</li>
                    <li>Managed budgets across 15+ clients, totaling over INR 3 Lakhs/month/client.</li>
                </ul>
            </div>
        </section>
        <section>
            <h3 class="section-title">Languages</h3>
            <div class="languages">
                <ul>
                    <li>English (Professional)</li>
                    <li>Odia (Native)</li>
                    <li>Hindi (Intermediate)</li>
                </ul>
                <ul>
                    <li>Bengali &amp; Nepali (Conversational)</li>
                    <li>German (Beginner)</li>
                </ul>
            </div>
        </section>
    </main>
    <footer>
        &copy; 2025 Dinesh Goutam Mohanty &mdash; Digital Marketing Manager
    </footer>
</body>
</html>
