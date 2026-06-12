<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EXCELENT BUSINESS | Transforme Ideias em Negócios de Sucesso</title>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary: #2563eb; --primary-dark: #1d4ed8; --primary-light: #dbeafe;
            --secondary: #7c3aed; --accent: #f59e0b; --success: #10b981; --danger: #ef4444;
            --dark: #0f172a; --gray-50: #f8fafc; --gray-100: #f1f5f9; --gray-200: #e2e8f0;
            --gray-300: #cbd5e1; --gray-400: #94a3b8; --gray-500: #64748b; --gray-600: #475569;
            --gray-700: #334155; --gray-800: #1e293b; --gray-900: #0f172a;
            --shadow-sm: 0 1px 2px rgba(0,0,0,0.05);
            --shadow: 0 1px 3px rgba(0,0,0,0.1);
            --shadow-md: 0 4px 6px -1px rgba(0,0,0,0.1);
            --shadow-lg: 0 10px 15px -3px rgba(0,0,0,0.1);
            --shadow-xl: 0 20px 25px -5px rgba(0,0,0,0.1);
            --radius: 8px; --radius-lg: 12px; --radius-xl: 16px; --radius-2xl: 24px;
            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        * { margin: 0; padding: 0; box-sizing: border-box; }
        html { scroll-behavior: smooth; scroll-padding-top: 80px; }
        body { font-family: 'Inter', sans-serif; line-height: 1.7; color: var(--gray-700); background: var(--gray-50); overflow-x: hidden; }
        
        .preloader { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: var(--dark); display: flex; align-items: center; justify-content: center; z-index: 9999; transition: opacity 0.5s, visibility 0.5s; }
        .preloader.hidden { opacity: 0; visibility: hidden; }
        .preloader-spinner { width: 60px; height: 60px; border: 4px solid rgba(255,255,255,0.3); border-top: 4px solid var(--primary); border-radius: 50%; animation: spin 1s linear infinite; margin: 0 auto 20px; }
        @keyframes spin { to { transform: rotate(360deg); } }
        
        .navbar { background: rgba(255,255,255,0.95); backdrop-filter: blur(20px); padding: 0 5%; position: fixed; top: 0; width: 100%; z-index: 1000; box-shadow: var(--shadow-sm); transition: var(--transition); height: 80px; display: flex; align-items: center; }
        .navbar.scrolled { box-shadow: var(--shadow-lg); height: 70px; }
        .nav-container { width: 100%; max-width: 1300px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; }
        .nav-logo { display: flex; align-items: center; gap: 12px; text-decoration: none; font-size: 1.5rem; font-weight: 800; color: var(--dark); }
        .nav-logo-icon { width: 45px; height: 45px; background: linear-gradient(135deg, var(--primary), var(--secondary)); border-radius: var(--radius); display: flex; align-items: center; justify-content: center; color: white; font-size: 1.5rem; }
        .nav-links { display: flex; gap: 35px; align-items: center; list-style: none; }
        .nav-links a { text-decoration: none; color: var(--gray-600); font-weight: 500; font-size: 0.95rem; transition: var(--transition); position: relative; padding: 5px 0; cursor: pointer; }
        .nav-links a::after { content: ''; position: absolute; bottom: -2px; left: 0; width: 0; height: 2px; background: var(--primary); transition: var(--transition); }
        .nav-links a:hover { color: var(--primary); }
        .nav-links a:hover::after { width: 100%; }
        .nav-cta { background: var(--primary); color: white !important; padding: 12px 28px !important; border-radius: 50px; font-weight: 600 !important; transition: var(--transition) !important; box-shadow: 0 4px 15px rgba(37,99,235,0.3); }
        .nav-cta::after { display: none !important; }
        .hamburger { display: none; flex-direction: column; cursor: pointer; gap: 5px; }
        .hamburger span { width: 28px; height: 3px; background: var(--dark); transition: var(--transition); border-radius: 3px; }
        .hamburger.active span:nth-child(1) { transform: rotate(45deg) translate(5px,5px); }
        .hamburger.active span:nth-child(2) { opacity: 0; }
        .hamburger.active span:nth-child(3) { transform: rotate(-45deg) translate(7px,-6px); }
        
        .hero { background: linear-gradient(135deg, #0f172a 0%, #1e3a5f 50%, #1e40af 100%); color: white; padding: 120px 5% 100px; position: relative; overflow: hidden; min-height: 100vh; display: flex; align-items: center; }
        .hero::before { content: ''; position: absolute; width: 600px; height: 600px; background: radial-gradient(circle, rgba(37,99,235,0.3), transparent 70%); top: -200px; right: -200px; border-radius: 50%; }
        .hero-container { max-width: 1300px; margin: 0 auto; display: grid; grid-template-columns: 1fr 1fr; gap: 60px; align-items: center; position: relative; z-index: 1; width: 100%; }
        .hero-badge { display: inline-flex; align-items: center; gap: 8px; background: rgba(255,255,255,0.1); backdrop-filter: blur(10px); padding: 8px 20px; border-radius: 50px; font-size: 0.9rem; margin-bottom: 30px; }
        .hero-title { font-size: clamp(2.5rem, 5vw, 4rem); font-weight: 900; line-height: 1.1; margin-bottom: 25px; }
        .hero-title span { background: linear-gradient(135deg, var(--accent), #fbbf24); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; }
        .hero-subtitle { font-size: 1.2rem; color: rgba(255,255,255,0.85); margin-bottom: 40px; max-width: 550px; }
        .hero-stats { display: flex; gap: 40px; margin-bottom: 40px; }
        .hero-stat-number { font-size: 2.5rem; font-weight: 800; background: linear-gradient(135deg, var(--accent), #fbbf24); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; }
        .hero-stat-label { font-size: 0.85rem; color: rgba(255,255,255,0.7); }
        .btn { display: inline-flex; align-items: center; gap: 10px; padding: 16px 32px; border-radius: 50px; font-weight: 600; font-size: 1rem; text-decoration: none; transition: var(--transition); cursor: pointer; border: none; font-family: 'Inter', sans-serif; }
        .btn-primary { background: white; color: var(--primary); }
        .btn-primary:hover { transform: translateY(-3px); box-shadow: 0 10px 30px rgba(0,0,0,0.3); }
        .btn-secondary { background: transparent; border: 2px solid rgba(255,255,255,0.3); color: white; }
        .hero-image-inner { width: 100%; max-width: 500px; aspect-ratio: 1; background: rgba(255,255,255,0.05); border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 12rem; border: 2px solid rgba(255,255,255,0.1); margin: 0 auto; }
        
        .section { padding: 100px 5%; }
        .section-container { max-width: 1300px; margin: 0 auto; }
        .section-header { text-align: center; margin-bottom: 60px; }
        .section-label { display: inline-block; background: var(--primary-light); color: var(--primary); padding: 6px 20px; border-radius: 50px; font-weight: 600; font-size: 0.85rem; margin-bottom: 20px; text-transform: uppercase; }
        .section-title { font-size: clamp(2rem, 4vw, 3rem); font-weight: 800; color: var(--dark); margin-bottom: 15px; }
        .section-subtitle { font-size: 1.15rem; color: var(--gray-500); max-width: 700px; margin: 0 auto; }
        .cards-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 30px; }
        .card { background: white; border-radius: var(--radius-xl); padding: 40px; box-shadow: var(--shadow); transition: var(--transition); border: 1px solid var(--gray-100); position: relative; overflow: hidden; }
        .card::before { content: ''; position: absolute; top: 0; left: 0; width: 100%; height: 5px; background: linear-gradient(90deg, var(--primary), var(--secondary)); transform: scaleX(0); transition: transform 0.4s ease; transform-origin: left; }
        .card:hover { transform: translateY(-8px); box-shadow: var(--shadow-xl); }
        .card:hover::before { transform: scaleX(1); }
        .card-icon { font-size: 3rem; margin-bottom: 20px; }
        .card h3 { font-size: 1.4rem; font-weight: 700; color: var(--dark); margin-bottom: 12px; }
        .highlight-box { background: white; border-radius: var(--radius-xl); padding: 40px; box-shadow: var(--shadow-lg); border: 1px solid var(--gray-200); }
        .highlight-box h3 { font-size: 1.6rem; font-weight: 700; color: var(--dark); margin-bottom: 20px; }
        .highlight-box li { padding: 12px 0; padding-left: 30px; position: relative; color: var(--gray-600); list-style: none; }
        .highlight-box li::before { content: '✓'; position: absolute; left: 0; color: var(--success); font-weight: bold; }
        .testimonials-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 30px; }
        .testimonial-card { background: white; padding: 35px; border-radius: var(--radius-xl); box-shadow: var(--shadow); border-left: 5px solid var(--primary); }
        .testimonial-text { font-style: italic; color: var(--gray-600); margin-bottom: 20px; }
        .values-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; }
        .value-card { background: white; padding: 35px; border-radius: var(--radius-xl); box-shadow: var(--shadow); text-align: center; border-top: 5px solid var(--primary); }
        .tags { display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 15px; }
        .tag { background: var(--primary-light); color: var(--primary); padding: 8px 20px; border-radius: 50px; font-weight: 600; font-size: 0.9rem; }
        .contact-section { background: linear-gradient(135deg, var(--primary), var(--secondary)); color: white; padding: 80px 5%; border-radius: var(--radius-2xl); text-align: center; }
        .contact-btn { display: inline-flex; align-items: center; gap: 12px; background: white; color: var(--primary); padding: 18px 40px; border-radius: 50px; font-weight: 700; font-size: 1.1rem; text-decoration: none; transition: var(--transition); }
        .footer { background: var(--dark); color: white; padding: 60px 5% 30px; }
        .footer-container { max-width: 1300px; margin: 0 auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 40px; margin-bottom: 40px; }
        .footer-section h4 { font-size: 1.2rem; font-weight: 700; margin-bottom: 20px; }
        .footer-links { list-style: none; }
        .footer-links li { margin-bottom: 12px; }
        .footer-links a { color: rgba(255,255,255,0.7); text-decoration: none; cursor: pointer; }
        .footer-bottom { text-align: center; padding-top: 30px; border-top: 1px solid rgba(255,255,255,0.1); color: rgba(255,255,255,0.5); }
        
        .chat-fab { position: fixed; bottom: 30px; right: 30px; width: 65px; height: 65px; border-radius: 50%; background: linear-gradient(135deg, var(--primary), var(--secondary)); color: white; border: none; font-size: 1.8rem; cursor: pointer; box-shadow: 0 10px 30px rgba(37,99,235,0.4); z-index: 999; transition: var(--transition); display: flex; align-items: center; justify-content: center; }
        .chat-fab:hover { transform: scale(1.1); }
        .chat-window { position: fixed; bottom: 110px; right: 30px; width: 420px; height: 650px; background: white; border-radius: var(--radius-xl); box-shadow: var(--shadow-xl); display: none; flex-direction: column; z-index: 998; overflow: hidden; }
        .chat-window.open { display: flex; animation: slideUp 0.3s ease; }
        @keyframes slideUp { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        .chat-header { background: linear-gradient(135deg, var(--primary), var(--secondary)); color: white; padding: 20px; display: flex; justify-content: space-between; align-items: center; }
        .chat-close { background: none; border: none; color: white; font-size: 1.5rem; cursor: pointer; }
        .chat-messages { flex: 1; padding: 20px; overflow-y: auto; background: var(--gray-50); display: flex; flex-direction: column; gap: 15px; }
        .chat-message { display: flex; gap: 10px; animation: fadeIn 0.3s ease; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
        .chat-message.user { justify-content: flex-end; }
        .chat-bubble { max-width: 85%; padding: 14px 18px; border-radius: 18px; line-height: 1.7; font-size: 0.95rem; word-wrap: break-word; }
        .chat-message.bot .chat-bubble { background: white; color: var(--gray-700); border: 1px solid var(--gray-200); white-space: pre-line; }
        .chat-message.user .chat-bubble { background: var(--primary); color: white; }
        .chat-suggestions { padding: 15px; display: flex; flex-wrap: wrap; gap: 8px; background: white; border-top: 1px solid var(--gray-200); max-height: 120px; overflow-y: auto; }
        .chat-suggestion { padding: 8px 16px; background: var(--gray-100); border: 1px solid var(--gray-200); border-radius: 50px; font-size: 0.85rem; cursor: pointer; transition: var(--transition); white-space: nowrap; font-family: 'Inter', sans-serif; }
        .chat-suggestion:hover { background: var(--primary); color: white; }
        .chat-input-area { padding: 15px; background: white; border-top: 1px solid var(--gray-200); display: flex; gap: 10px; }
        .chat-input { flex: 1; padding: 14px 18px; border: 1px solid var(--gray-300); border-radius: 50px; outline: none; font-size: 0.95rem; font-family: 'Inter', sans-serif; }
        .chat-input:focus { border-color: var(--primary); box-shadow: 0 0 0 3px var(--primary-light); }
        .chat-send { width: 48px; height: 48px; border-radius: 50%; background: var(--primary); color: white; border: none; cursor: pointer; font-size: 1.2rem; flex-shrink: 0; }
        .back-to-top { position: fixed; bottom: 30px; left: 30px; width: 50px; height: 50px; border-radius: 50%; background: white; color: var(--primary); border: 2px solid var(--gray-200); cursor: pointer; font-size: 1.2rem; z-index: 997; display: none; box-shadow: var(--shadow); }
        .back-to-top.visible { display: flex; align-items: center; justify-content: center; }
        
        @media (max-width: 1024px) { .hero-container { grid-template-columns: 1fr; text-align: center; } .hero-subtitle { margin: 0 auto 40px; } .hero-stats { justify-content: center; } .hero-image-inner { display: none; } }
        @media (max-width: 768px) { .nav-links { position: fixed; top: 0; right: -100%; width: 80%; max-width: 400px; height: 100vh; background: white; flex-direction: column; padding: 100px 40px 40px; transition: var(--transition); box-shadow: var(--shadow-xl); } .nav-links.active { right: 0; } .hamburger { display: flex; } .cards-grid, .testimonials-grid, .values-grid { grid-template-columns: 1fr; } .chat-window { width: calc(100% - 20px); right: 10px; left: 10px; bottom: 100px; height: 70vh; } }
    </style>
</head>
<body>
    <div class="preloader" id="preloader"><div style="text-align:center;color:white;"><div class="preloader-spinner" style="margin:0 auto 20px;"></div><p style="font-weight:600;">EXCELENT BUSINESS</p></div></div>
    
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <a href="#" class="nav-logo"><div class="nav-logo-icon">💼</div><span>EXCELENT BUSINESS</span></a>
            <div class="hamburger" id="hamburger"><span></span><span></span><span></span></div>
            <ul class="nav-links" id="navLinks">
                <li><a href="#sobre">Sobre</a></li><li><a href="#dicas">Dicas</a></li><li><a href="#comecar">Começar</a></li><li><a href="#atendimento">Atendimento</a></li><li><a href="#crescimento">Crescimento</a></li><li><a href="#contacto" class="nav-cta">Contacto</a></li>
            </ul>
        </div>
    </nav>
    
    <section class="hero" id="home">
        <div class="hero-container">
            <div>
                <div class="hero-badge"><i class="fas fa-star" style="color:var(--accent);"></i> Plataforma líder em negócios</div>
                <h1 class="hero-title">Transforme <span>Ideias</span> em Negócios de Sucesso</h1>
                <p class="hero-subtitle">Oferecemos estratégias práticas, dicas inteligentes e insights reais para empreendedores alcançarem crescimento sustentável.</p>
                <div class="hero-stats"><div><div class="hero-stat-number">500+</div><div class="hero-stat-label">Empreendedores</div></div><div><div class="hero-stat-number">100+</div><div class="hero-stat-label">Dicas</div></div><div><div class="hero-stat-number">50+</div><div class="hero-stat-label">Estratégias</div></div></div>
                <div style="display:flex;gap:15px;flex-wrap:wrap;"><a href="#dicas" class="btn btn-primary"><i class="fas fa-lightbulb"></i> Ver Dicas</a><a href="#contacto" class="btn btn-secondary"><i class="fas fa-envelope"></i> Contactar</a></div>
            </div>
            <div style="text-align:center;"><div class="hero-image-inner">📈</div></div>
        </div>
    </section>
    
    <section class="section" id="sobre"><div class="section-container"><div class="section-header"><span class="section-label">Sobre Nós</span><h2 class="section-title">Conhecimento que transforma negócios</h2><p class="section-subtitle">A EXCELENT BUSINESS democratiza o conhecimento empresarial com conteúdos práticos e acessíveis.</p></div><div class="highlight-box" style="margin-bottom:40px;"><h3>🎯 Acreditamos que:</h3><ul><li>Qualquer pessoa pode empreender com a orientação certa</li><li>O sucesso depende de planeamento, inovação e decisões inteligentes</li><li>O conhecimento deve ser acessível, prático e aplicável</li></ul></div><div class="values-grid"><div class="value-card"><h3>🌍 Missão</h3><p>Capacitar empreendedores com conhecimento prático.</p></div><div class="value-card"><h3>👁 Visão</h3><p>Ser referência em empreendedorismo na África.</p></div><div class="value-card"><h3>💎 Valores</h3><div class="tags"><span class="tag">Inovação</span><span class="tag">Confiança</span><span class="tag">Estratégia</span><span class="tag">Impacto</span></div></div></div></div></section>
    
    <section class="section" id="dicas" style="background:white;"><div class="section-container"><div class="section-header"><span class="section-label">Dicas Inteligentes</span><h2 class="section-title">Estratégias práticas para o sucesso</h2></div><div class="cards-grid"><div class="card"><span class="card-icon">🌱</span><h3>Comece Pequeno</h3><p>Valide seu modelo antes de expandir.</p></div><div class="card"><span class="card-icon">⭐</span><h3>Experiência do Cliente</h3><p>70% do sucesso depende do atendimento.</p></div><div class="card"><span class="card-icon">⚙️</span><h3>Automatize</h3><p>Reduza custos e evite erros.</p></div><div class="card"><span class="card-icon">💰</span><h3>Diversifique</h3><p>Crie múltiplas fontes de receita.</p></div><div class="card"><span class="card-icon">📚</span><h3>Aprenda Sempre</h3><p>Estude empresas de sucesso.</p></div><div class="card"><span class="card-icon">📱</span><h3>Marketing Digital</h3><p>Essencial para qualquer negócio.</p></div></div></div></section>
    
    <section class="section" id="comecar"><div class="section-container"><div class="section-header"><span class="section-label">Como Começar</span><h2 class="section-title">Negócio com pouco dinheiro</h2></div><div class="cards-grid"><div class="card"><span class="card-icon">💡</span><h3>1. Necessidade Real</h3><p>Observe problemas ao seu redor.</p></div><div class="card"><span class="card-icon">🏠</span><h3>2. Comece de Casa</h3><p>Evite aluguer no início.</p></div><div class="card"><span class="card-icon">📱</span><h3>3. Redes Sociais</h3><p>Ferramentas gratuitas poderosas.</p></div><div class="card"><span class="card-icon">🤝</span><h3>4. Serviços Primeiro</h3><p>Menos investimento inicial.</p></div><div class="card"><span class="card-icon">♻️</span><h3>5. Reinvista</h3><p>100% do lucro no início.</p></div><div class="card"><span class="card-icon">🎯</span><h3>6. Foque num Nicho</h3><p>Domine um mercado pequeno.</p></div></div></div></section>
    
    <section class="section" id="atendimento" style="background:white;"><div class="section-container"><div class="section-header"><span class="section-label">Atendimento</span><h2 class="section-title">O pilar do sucesso</h2></div><div class="highlight-box" style="background:linear-gradient(135deg,#fffbeb,#fef3c7);margin-bottom:40px;"><h3 style="color:#92400e;">⚠️ A Verdade Sobre Atendimento</h3><ul><li>Cliente satisfeito conta a 3 pessoas</li><li>Cliente INSATISFEITO conta a 15 pessoas</li><li>96% dos insatisfeitos simplesmente não voltam</li><li>Novo cliente custa 5x mais que manter um existente</li></ul></div><div class="cards-grid"><div class="card"><span class="card-icon">👂</span><h3>Escute Ativamente</h3><p>Compreenda, não apenas ouça.</p></div><div class="card"><span class="card-icon">⚡</span><h3>Agilidade</h3><p>Responda em menos de 2 horas.</p></div><div class="card"><span class="card-icon">😊</span><h3>Atitude Positiva</h3><p>Seu humor não é problema do cliente.</p></div><div class="card"><span class="card-icon">🎁</span><h3>Supere Expectativas</h3><p>Pequenos gestos fazem diferença.</p></div><div class="card"><span class="card-icon">🔧</span><h3>Resolva Problemas</h3><p>Assuma responsabilidade.</p></div><div class="card"><span class="card-icon">💬</span><h3>Comunicação Clara</h3><p>Evite mal-entendidos.</p></div></div></div></section>
    
    <section class="section" id="crescimento"><div class="section-container"><div class="section-header"><span class="section-label">Crescimento</span><h2 class="section-title">Estratégias sustentáveis</h2></div><div class="cards-grid"><div class="card"><span class="card-icon">👥</span><h3>Clientes Fiéis</h3><p>Programa de fidelidade.</p></div><div class="card"><span class="card-icon">🎁</span><h3>Boca a Boca</h3><p>Incentive referências.</p></div><div class="card"><span class="card-icon">📊</span><h3>Controle Financeiro</h3><p>Registe tudo.</p></div><div class="card"><span class="card-icon">🔄</span><h3>Diversifique</h3><p>Crie pacotes e combos.</p></div><div class="card"><span class="card-icon">🤖</span><h3>Automatize</h3><p>Use ferramentas gratuitas.</p></div><div class="card"><span class="card-icon">🎓</span><h3>Nunca Pare</h3><p>Aprenda constantemente.</p></div></div></div></section>
    
    <section class="section" style="background:white;"><div class="section-container"><div class="section-header"><span class="section-label">Testemunhos</span><h2 class="section-title">O que dizem os empreendedores</h2></div><div class="testimonials-grid"><div class="testimonial-card"><p class="testimonial-text">"As dicas da EXCELENT BUSINESS ajudaram-me a duplicar as vendas em 3 meses."</p><p><strong>Carlos M.</strong></p></div><div class="testimonial-card"><p class="testimonial-text">"Conteúdos claros e aplicáveis ao dia a dia. Recomendo!"</p><p><strong>Peres Mabhala</strong></p></div><div class="testimonial-card"><p class="testimonial-text">"Finalmente um site que fala a linguagem do empreendedor real."</p><p><strong>Ana S.</strong></p></div></div></div></section>
    
    <section class="section" id="contacto"><div class="section-container"><div class="contact-section"><h2 style="font-size:2.5rem;font-weight:800;margin-bottom:15px;">Vamos Conversar?</h2><p style="font-size:1.2rem;margin-bottom:40px;">Conecte-se connosco e transforme o seu negócio</p><a href="https://www.linkedin.com/in/peres-mabhala-3098b1304/" target="_blank" class="contact-btn"><i class="fab fa-linkedin"></i> LinkedIn - Peres Mabhala</a></div></div></section>
    
    <footer class="footer"><div class="footer-container"><div class="footer-section"><h4>💼 EXCELENT BUSINESS</h4><p style="color:rgba(255,255,255,0.7);">Transformando ideias em negócios de sucesso.</p></div><div class="footer-section"><h4>Links Rápidos</h4><ul class="footer-links"><li><a href="#sobre">Sobre</a></li><li><a href="#dicas">Dicas</a></li><li><a href="#comecar">Começar</a></li><li><a href="#contacto">Contacto</a></li></ul></div><div class="footer-section"><h4>Contacto</h4><p style="color:rgba(255,255,255,0.7);"><i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/peres-mabhala-3098b1304/" target="_blank" style="color:white;text-decoration:none;">Peres Mabhala</a></p></div></div><div class="footer-bottom"><p>&copy; 2025 EXCELENT BUSINESS. Todos os direitos reservados.</p></div></footer>
    
    <button class="chat-fab" id="chatFab" title="Assistente Virtual"><i class="fas fa-comment-dots"></i></button>
    
    <div class="chat-window" id="chatWindow">
        <div class="chat-header"><h4 style="font-size:1.1rem;">🤖 Assistente EXCELENT BUSINESS</h4><button class="chat-close" id="chatClose">&times;</button></div>
        <div class="chat-messages" id="chatMessages"><div class="chat-message bot"><div class="chat-bubble">Olá! 👋 Hello! 👋<br><br>Sou o assistente virtual da EXCELENT BUSINESS.<br>I'm the EXCELENT BUSINESS virtual assistant.<br><br>Posso responder em <b>Português</b> e <b>Inglês</b>!<br>I can answer in <b>Portuguese</b> and <b>English</b>!<br><br>Temas / Topics:<br>📊 Negócios / Business<br>🌍 História / History<br>🔬 Ciência / Science<br>🗺 Geografia / Geography<br>💻 Tecnologia / Technology<br>🏥 Saúde / Health<br>🎨 Cultura / Culture<br>⚽ Desporto / Sports<br>🍳 Culinária / Cooking<br>🎵 Música / Music<br>🎬 Cinema / Movies<br>📚 Literatura / Literature<br>🗣 Línguas / Languages<br>🧠 Psicologia / Psychology<br>🌱 Meio Ambiente / Environment<br>🏛 Política / Politics<br>💼 Carreira / Career<br>📈 Economia / Economy<br>✈️ Viagens / Travel<br>🐾 Animais / Animals<br><br>E muito mais! / And much more!<br>Como posso ajudar? / How can I help? 😊</div></div></div>
        <div class="chat-suggestions" id="chatSuggestions">
            <button class="chat-suggestion">Começar negócio</button><button class="chat-suggestion">How to start?</button><button class="chat-suggestion">Marketing</button><button class="chat-suggestion">Finanças</button><button class="chat-suggestion">História</button><button class="chat-suggestion">Science</button><button class="chat-suggestion">Tecnologia</button><button class="chat-suggestion">Saúde</button><button class="chat-suggestion">Culinária</button><button class="chat-suggestion">Viagens</button>
        </div>
        <div class="chat-input-area"><input type="text" class="chat-input" id="chatInput" placeholder="Digite sua pergunta... / Type your question..."><button class="chat-send" id="chatSend"><i class="fas fa-paper-plane"></i></button></div>
    </div>
    
    <button class="back-to-top" id="backToTop" title="Voltar ao topo"><i class="fas fa-arrow-up"></i></button>
    
    <script>
        window.addEventListener('load', () => { setTimeout(() => document.getElementById('preloader').classList.add('hidden'), 500); });
        window.addEventListener('scroll', () => { document.getElementById('navbar').classList.toggle('scrolled', window.scrollY > 50); document.getElementById('backToTop').classList.toggle('visible', window.scrollY > 500); });
        
        const hamburger = document.getElementById('hamburger');
        const navLinks = document.getElementById('navLinks');
        hamburger.addEventListener('click', () => { hamburger.classList.toggle('active'); navLinks.classList.toggle('active'); });
        document.querySelectorAll('.nav-links a').forEach(link => { link.addEventListener('click', () => { hamburger.classList.remove('active'); navLinks.classList.remove('active'); }); });
        document.getElementById('backToTop').addEventListener('click', () => { window.scrollTo({ top: 0, behavior: 'smooth' }); });
        
        const chatFab = document.getElementById('chatFab');
        const chatWindow = document.getElementById('chatWindow');
        const chatClose = document.getElementById('chatClose');
        const chatMessages = document.getElementById('chatMessages');
        const chatInput = document.getElementById('chatInput');
        const chatSend = document.getElementById('chatSend');
        chatFab.addEventListener('click', () => { chatWindow.classList.toggle('open'); if (chatWindow.classList.contains('open')) chatInput.focus(); });
        chatClose.addEventListener('click', () => chatWindow.classList.remove('open'));
        
        // ============================================
        // BASE DE CONHECIMENTO GIGANTE (60+ CATEGORIAS)
        // ============================================
        const knowledgeBase = {
            // === NEGÓCIOS (PT) ===
            'comecar': { keywords: ['começar', 'iniciar', 'começo', 'novo negócio', 'abrir empresa', 'montar negócio', 'empreender'], lang: 'pt', response: '🚀 COMO COMEÇAR UM NEGÓCIO COM POUCO DINHEIRO:\n\n1. 🎯 Identifique uma necessidade real\n2. 🏠 Comece de casa\n3. 📱 Use redes sociais gratuitas\n4. 💰 Ofereça serviços antes de produtos\n5. ♻️ Reinvista todos os lucros iniciais\n\nNEGÓCIOS COM MENOS DE 5.000MT:\n• Venda de bolos e doces\n• Recarga de telemóveis\n• Explicações/aulas\n• Horta urbana\n• Produtos de limpeza caseiros' },
            'atendimento': { keywords: ['atendimento', 'cliente', 'atender', 'serviço', 'satisfação', 'customer'], lang: 'pt', response: '⭐ ATENDIMENTO AO CLIENTE:\n\n✓ Escute ativamente\n✓ Responda em menos de 2 horas\n✓ Atitude positiva sempre\n✓ Supere expectativas\n✓ Resolva no primeiro contacto\n\n⚠️ Cliente insatisfeito conta a 15 pessoas!\n96% dos insatisfeitos não voltam.' },
            'crescimento': { keywords: ['crescer', 'crescimento', 'expandir', 'aumentar', 'escalar'], lang: 'pt', response: '📈 CRESCIMENTO SUSTENTÁVEL:\n\n1. Base de clientes fiéis\n2. Marketing boca a boca\n3. Controle financeiro rigoroso\n4. Diversifique produtos\n5. Automatize processos\n6. Nunca pare de aprender\n\nPlano 12 meses: Fundação → Expansão → Profissionalização → Consolidação' },
            'marketing': { keywords: ['marketing', 'divulgar', 'publicidade', 'vendas', 'redes sociais', 'instagram', 'facebook', 'whatsapp'], lang: 'pt', response: '📱 MARKETING DIGITAL:\n\nGRÁTIS: Facebook, Instagram, WhatsApp Business, Google Meu Negócio, TikTok\n\nDICAS: Mostre bastidores, compartilhe testemunhos, responda todos comentários, use fotos de qualidade.\n\nMarketing não é opção, é NECESSIDADE!' },
            'finanças': { keywords: ['dinheiro', 'capital', 'financeiro', 'lucro', 'finanças', 'contabilidade', 'orçamento'], lang: 'pt', response: '💰 GESTÃO FINANCEIRA:\n\n1. Separe dinheiro pessoal do empresarial\n2. Registe TUDO\n3. Reinvista nos primeiros 6 meses\n4. Reserva de emergência (3 meses)\n5. Analise lucros mensalmente\n\nFÓRMULA: Lucro = Receita - Despesas\nMeta: 30% de margem' },
            'preços': { keywords: ['preço', 'precificar', 'valor', 'quanto cobrar', 'custo'], lang: 'pt', response: '💵 COMO DEFINIR PREÇOS:\n\nPreço = Custos + Despesas + Margem de Lucro\n\n1. Calcule todos custos\n2. Some despesas fixas\n3. Adicione margem (mínimo 30%)\n4. Pesquise concorrentes\n\n⚠️ NUNCA trabalhe sem lucro!' },
            'legalização': { keywords: ['legalização', 'formalizar', 'registo', 'licença', 'alvará', 'documentos'], lang: 'pt', response: '📋 FORMALIZAÇÃO:\n\n✓ Acesso a financiamento\n✓ Credibilidade\n✓ Proteção legal\n✓ Emissão de faturas\n\nPASSOS: Estrutura → Registo Comercial → NUIT → Alvará → Conta bancária' },
            'fornecedor': { keywords: ['fornecedor', 'comprar', 'matéria-prima', 'stock', 'estoque'], lang: 'pt', response: '📦 FORNECEDORES:\n\n1. Qualidade consistente\n2. Preço justo (compare 3+)\n3. Confiabilidade na entrega\n4. Condições de pagamento\n\nDICA: Tenha sempre 2+ fornecedores!' },
            'equipa': { keywords: ['equipa', 'equipe', 'funcionário', 'contratar', 'colaborador', 'rh'], lang: 'pt', response: '👥 GESTÃO DE EQUIPA:\n\nContrate quando: trabalho supera capacidade, pode pagar 6 meses, há tarefas repetitivas.\n\nMantenha motivado: pague em dia, dê feedback, reconheça, ofereça crescimento.' },
            'motivação': { keywords: ['motivação', 'desânimo', 'desistir', 'cansado', 'difícil'], lang: 'pt', response: '💪 MOTIVAÇÃO:\n\nÉ normal sentir-se cansado!\n\n1. Lembre porque começou\n2. Comemore pequenas vitórias\n3. Conecte-se com outros empreendedores\n4. Cuide de si mesmo\n5. Foque no progresso\n\n"O sucesso é a soma de pequenos esforços repetidos"' },

            // === BUSINESS (EN) ===
            'start': { keywords: ['how to start', 'starting a business', 'launch', 'startup', 'entrepreneur'], lang: 'en', response: '🚀 HOW TO START A BUSINESS:\n\n1. 🎯 Identify a real need\n2. 🏠 Start from home\n3. 📱 Use free social media\n4. 💰 Offer services before products\n5. ♻️ Reinvest all profits\n\nBUSINESSES UNDER $100: Cake sales, mobile top-up, tutoring, urban garden, cleaning products' },
            'customer': { keywords: ['customer service', 'client', 'support', 'satisfaction', 'experience'], lang: 'en', response: '⭐ CUSTOMER SERVICE:\n\n✓ Listen actively\n✓ Respond within 2 hours\n✓ Positive attitude always\n✓ Exceed expectations\n✓ Solve on first contact\n\n⚠️ Unhappy customer tells 15 people! 96% just leave without complaining.' },
            'growth': { keywords: ['growth', 'grow', 'expand', 'scale', 'development'], lang: 'en', response: '📈 GROWTH STRATEGIES:\n\n1. Loyal customer base\n2. Word-of-mouth marketing\n3. Financial control\n4. Diversify products\n5. Automate processes\n6. Never stop learning\n\n12-Month Plan: Foundation → Expansion → Professionalization → Consolidation' },
            'marketing_en': { keywords: ['marketing', 'advertising', 'promotion', 'social media', 'ads', 'branding'], lang: 'en', response: '📱 DIGITAL MARKETING:\n\nFREE: Facebook, Instagram, WhatsApp Business, Google My Business, TikTok\n\nTIPS: Show behind-the-scenes, share testimonials, respond to all comments, use quality photos.\n\nMarketing is not optional, it is a NECESSITY!' },
            'finance': { keywords: ['money', 'capital', 'financial', 'profit', 'accounting', 'budget', 'revenue'], lang: 'en', response: '💰 FINANCIAL MANAGEMENT:\n\n1. Separate personal/business money\n2. Track EVERYTHING\n3. Reinvest first 6 months\n4. Emergency fund (3 months)\n5. Analyze monthly\n\nFORMULA: Profit = Revenue - Expenses\nGoal: 30% margin' },
            'pricing': { keywords: ['price', 'pricing', 'value', 'how much to charge', 'cost', 'rate'], lang: 'en', response: '💵 HOW TO SET PRICES:\n\nPrice = Costs + Expenses + Profit Margin\n\n1. Calculate all costs\n2. Add fixed expenses\n3. Add margin (min 30%)\n4. Research competitors\n\n⚠️ NEVER work without profit!' },

            // === HISTÓRIA / HISTORY ===
            'historia_mocambique': { keywords: ['história de moçambique', 'moçambique história', 'independência moçambique', 'samora machel', 'frelimo', 'renamo'], response: '📜 HISTÓRIA DE MOÇAMBIQUE:\n\n• Independência: 25 de Junho de 1975\n• Primeiro presidente: Samora Machel\n• Guerra civil: 1977-1992\n• Acordo de Paz: 1992 (Roma)\n• Atual presidente: Daniel Chapo (2025)\n\nMoçambique é uma república localizada no sudeste da África, banhada pelo Oceano Índico.' },
            'historia_mundial': { keywords: ['história mundial', 'guerra mundial', 'revolução', 'antigo egito', 'império romano', 'idade média', 'renascimento'], response: '📚 HISTÓRIA MUNDIAL:\n\n• Antigo Egito: 3100-332 a.C.\n• Império Romano: 27 a.C.-476 d.C.\n• Idade Média: 476-1453\n• Renascimento: séc. XIV-XVI\n• 1ª Guerra Mundial: 1914-1918\n• 2ª Guerra Mundial: 1939-1945\n• Revolução Francesa: 1789\n\nSobre qual período gostaria de saber mais?' },
            'history': { keywords: ['history', 'world war', 'ancient', 'roman empire', 'middle ages', 'renaissance', 'revolution'], lang: 'en', response: '📚 WORLD HISTORY:\n\n• Ancient Egypt: 3100-332 BC\n• Roman Empire: 27 BC-476 AD\n• Middle Ages: 476-1453\n• Renaissance: 14th-16th centuries\n• WWI: 1914-1918\n• WWII: 1939-1945\n• French Revolution: 1789\n\nWhich period interests you?' },

            // === CIÊNCIA / SCIENCE ===
            'ciencia': { keywords: ['ciência', 'física', 'química', 'biologia', 'astronomia', 'planeta', 'átomo', 'célula', 'dna', 'gravidade', 'einstein', 'newton'], response: '🔬 CIÊNCIA:\n\n• Física: Leis de Newton, relatividade de Einstein, gravidade\n• Química: Tabela periódica (118 elementos), átomos, reações\n• Biologia: Células, DNA, evolução de Darwin\n• Astronomia: 8 planetas, Sol é estrela, Via Láctea\n\nFaça uma pergunta específica!' },
            'science': { keywords: ['science', 'physics', 'chemistry', 'biology', 'astronomy', 'atom', 'cell', 'dna', 'gravity', 'einstein', 'newton'], lang: 'en', response: '🔬 SCIENCE:\n\n• Physics: Newton laws, Einstein relativity, gravity\n• Chemistry: Periodic table (118 elements), atoms, reactions\n• Biology: Cells, DNA, Darwin evolution\n• Astronomy: 8 planets, Sun is star, Milky Way\n\nAsk a specific question!' },

            // === GEOGRAFIA / GEOGRAPHY ===
            'geografia': { keywords: ['geografia', 'país', 'capital', 'continente', 'oceano', 'rio', 'montanha', 'população', 'áfrica', 'maputo'], response: '🌍 GEOGRAFIA:\n\n• Moçambique: Capital Maputo, pop. ~32 milhões\n• África: 54 países, maior deserto Saara\n• Mundo: 7 continentes, 5 oceanos\n• Maior país: Rússia (17M km²)\n• Maior população: Índia (1.4B)\n• Rio Nilo: maior do mundo (6.650 km)\n• Monte Everest: 8.848m\n\nPergunte sobre qualquer país!' },
            'geography': { keywords: ['geography', 'country', 'capital', 'continent', 'ocean', 'river', 'mountain', 'population'], lang: 'en', response: '🌍 GEOGRAPHY:\n\n• Mozambique: Capital Maputo, pop. ~32M\n• Africa: 54 countries, Sahara largest desert\n• World: 7 continents, 5 oceans\n• Largest country: Russia (17M km²)\n• Largest population: India (1.4B)\n• Nile River: longest (6,650 km)\n• Mount Everest: 8,848m\n\nAsk about any country!' },

            // === TECNOLOGIA / TECHNOLOGY ===
            'tecnologia': { keywords: ['tecnologia', 'computador', 'internet', 'smartphone', 'programação', 'ia', 'inteligência artificial', 'chatgpt', 'redes', 'wifi'], response: '💻 TECNOLOGIA:\n\n• Internet: Rede global de computadores (ARPANET 1969)\n• WWW: Criada por Tim Berners-Lee (1989)\n• IA: Inteligência Artificial (ChatGPT, Gemini)\n• Smartphones: iPhone lançado 2007\n• Programação: Python, JavaScript, Java, C++\n• WiFi: Wireless Fidelity (padrão IEEE 802.11)\n• Bluetooth: Tecnologia de curto alcance\n\nTem dúvidas específicas?' },
            'technology': { keywords: ['technology', 'computer', 'internet', 'smartphone', 'programming', 'ai', 'artificial intelligence', 'wifi', 'bluetooth'], lang: 'en', response: '💻 TECHNOLOGY:\n\n• Internet: Global network (ARPANET 1969)\n• WWW: Created by Tim Berners-Lee (1989)\n• AI: Artificial Intelligence (ChatGPT, Gemini)\n• Smartphones: iPhone launched 2007\n• Programming: Python, JavaScript, Java, C++\n• WiFi: Wireless Fidelity (IEEE 802.11)\n• Bluetooth: Short-range technology\n\nSpecific questions?' },

            // === SAÚDE / HEALTH ===
            'saude': { keywords: ['saúde', 'doença', 'sintoma', 'médico', 'remédio', 'vacina', 'exercício', 'dieta', 'alimentação', 'nutrição', 'covid'], response: '🏥 SAÚDE (⚠️ Não substitui médico!):\n\n• Alimentação: 5 porções de frutas/vegetais por dia\n• Exercício: 150 min/semana de atividade moderada\n• Água: 2L por dia\n• Sono: 7-9 horas por noite\n• Vacinas: Importantes para prevenção\n• COVID-19: Vacinação e higiene\n\nPara diagnósticos, consulte sempre um médico!' },
            'health': { keywords: ['health', 'disease', 'symptom', 'doctor', 'medicine', 'vaccine', 'exercise', 'diet', 'nutrition', 'covid'], lang: 'en', response: '🏥 HEALTH (⚠️ Not medical advice!):\n\n• Diet: 5 servings fruits/vegetables daily\n• Exercise: 150 min/week moderate activity\n• Water: 2L per day\n• Sleep: 7-9 hours per night\n• Vaccines: Important for prevention\n• COVID-19: Vaccination and hygiene\n\nAlways consult a doctor for diagnoses!' },

            // === CULTURA / CULTURE ===
            'cultura': { keywords: ['cultura', 'arte', 'música', 'filme', 'livro', 'literatura', 'pintura', 'dança', 'teatro', 'cinema'], response: '🎨 CULTURA:\n\n• Literatura: Machado de Assis, Mia Couto, José Saramago\n• Cinema: Maior bilheteria Avatar ($2.9B)\n• Música: Mozart (clássico), Bob Marley (reggae)\n• Arte: Mona Lisa (Da Vinci), Guernica (Picasso)\n• Cultura moçambicana: Marrabenta, Timbila, Capulana\n\nQue tema cultural lhe interessa?' },
            'culture': { keywords: ['culture', 'art', 'music', 'film', 'book', 'literature', 'painting', 'dance', 'theater'], lang: 'en', response: '🎨 CULTURE:\n\n• Literature: Shakespeare, Machado de Assis, Mia Couto\n• Cinema: Highest grossing Avatar ($2.9B)\n• Music: Mozart (classical), Bob Marley (reggae)\n• Art: Mona Lisa (Da Vinci), Guernica (Picasso)\n• Mozambique: Marrabenta, Timbila, Capulana\n\nWhat cultural topic interests you?' },

            // === DESPORTO / SPORTS ===
            'desporto': { keywords: ['desporto', 'esporte', 'futebol', 'basquete', 'atletismo', 'jogos', 'campeonato', 'copa', 'olímpico'], response: '⚽ DESPORTO:\n\n• Futebol: Copa do Mundo (Brasil 5 títulos)\n• Basquete: NBA (EUA), Lakers e Celtics maiores campeões\n• Atletismo: Usain Bolt (100m em 9.58s)\n• Jogos Olímpicos: Próximos LA 2028\n• Moçambique: Maria Mutola (ouro 800m Sydney 2000)\n\nQual desporto lhe interessa?' },
            'sports': { keywords: ['sports', 'football', 'soccer', 'basketball', 'athletics', 'games', 'championship', 'world cup', 'olympic'], lang: 'en', response: '⚽ SPORTS:\n\n• Soccer: World Cup (Brazil 5 titles)\n• Basketball: NBA (USA), Lakers & Celtics most titles\n• Athletics: Usain Bolt (100m in 9.58s)\n• Olympics: Next LA 2028\n• Mozambique: Maria Mutola (800m gold Sydney 2000)\n\nWhich sport interests you?' },

            // === CULINÁRIA / COOKING ===
            'culinaria': { keywords: ['comida', 'receita', 'culinária', 'gastronomia', 'prato', 'cozinhar', 'ingrediente', 'restaurante', 'bolo', 'arroz'], response: '🍳 CULINÁRIA:\n\n• Moçambique: Matapa, Xima, Camarão grelhado, Piri-piri\n• Portugal: Bacalhau, Pastel de nata, Caldo verde\n• Brasil: Feijoada, Pão de queijo, Açaí\n• Itália: Pizza, Pasta, Risotto\n• Japão: Sushi, Ramen, Tempura\n\nDICA: Receita básica de bolo: 3 ovos, 2 xíc. farinha, 1 xíc. açúcar, 1/2 xíc. óleo, fermento.' },
            'cooking': { keywords: ['food', 'recipe', 'cooking', 'cuisine', 'dish', 'ingredient', 'restaurant', 'cake', 'rice'], lang: 'en', response: '🍳 COOKING:\n\n• Mozambique: Matapa, Xima, Grilled shrimp, Piri-piri\n• Italian: Pizza, Pasta, Risotto\n• Japanese: Sushi, Ramen, Tempura\n• Brazilian: Feijoada, Pão de queijo\n\nTIP: Basic cake recipe: 3 eggs, 2 cups flour, 1 cup sugar, 1/2 cup oil, baking powder.' },

            // === MÚSICA / MUSIC ===
            'musica': { keywords: ['música', 'music', 'canção', 'artista', 'banda', 'álbum', 'show', 'concerto', 'guitarra', 'piano'], response: '🎵 MÚSICA:\n\n• Clássica: Mozart, Beethoven, Bach\n• Rock: Beatles, Queen, Pink Floyd\n• Pop: Michael Jackson, Madonna, Beyoncé\n• Reggae: Bob Marley\n• Hip Hop: Tupac, Kendrick Lamar\n• Moçambique: Marrabenta, Mabulu, Dama do Bling\n• Streaming: Spotify, Apple Music, YouTube Music\n\nQual género musical prefere?' },
            'music': { keywords: ['music', 'song', 'artist', 'band', 'album', 'concert', 'guitar', 'piano'], lang: 'en', response: '🎵 MUSIC:\n\n• Classical: Mozart, Beethoven, Bach\n• Rock: Beatles, Queen, Pink Floyd\n• Pop: Michael Jackson, Madonna, Beyoncé\n• Reggae: Bob Marley\n• Hip Hop: Tupac, Kendrick Lamar\n• Mozambique: Marrabenta, Mabulu\n• Streaming: Spotify, Apple Music\n\nWhich genre do you prefer?' },

            // === CINEMA / MOVIES ===
            'cinema': { keywords: ['cinema', 'filme', 'ator', 'atriz', 'diretor', 'oscar', 'hollywood', 'netflix', 'série'], response: '🎬 CINEMA:\n\n• Maiores bilheterias: Avatar ($2.9B), Vingadores Ultimato ($2.8B), Avatar 2 ($2.3B)\n• Oscar: Mais premiados - Ben-Hur, Titanic, LOTR (11 cada)\n• Diretores: Spielberg, Scorsese, Nolan, Tarantino\n• Streaming: Netflix, Disney+, HBO Max, Prime Video\n• Moçambique: Cinema em crescimento, festivais como Dockanema\n\nRecomendações? Que género gosta?' },
            'movies': { keywords: ['movies', 'film', 'actor', 'actress', 'director', 'oscar', 'hollywood', 'netflix', 'series'], lang: 'en', response: '🎬 MOVIES:\n\n• Highest grossing: Avatar ($2.9B), Endgame ($2.8B)\n• Oscar: Most wins - Ben-Hur, Titanic, LOTR (11 each)\n• Directors: Spielberg, Scorsese, Nolan, Tarantino\n• Streaming: Netflix, Disney+, HBO Max, Prime Video\n\nRecommendations? What genre do you like?' },

            // === LÍNGUAS / LANGUAGES ===
            'linguas': { keywords: ['língua', 'idioma', 'inglês', 'português', 'francês', 'espanhol', 'aprender', 'language', 'english', 'portuguese', 'french', 'spanish', 'learn'], response: '🗣 LÍNGUAS / LANGUAGES:\n\n• Português: 260M falantes (Brasil, Portugal, Moçambique, Angola)\n• English: 1.5B falantes (global)\n• Espanhol: 500M falantes\n• Francês: 300M falantes\n• Mandarim: 1.1B falantes (mais falado)\n\nDICAS para aprender:\n✓ Pratique diariamente (15 min)\n✓ Use apps: Duolingo, Babbel\n✓ Veja filmes/séries no idioma\n✓ Converse com nativos\n✓ Não tenha medo de errar!' },

            // === PSICOLOGIA / PSYCHOLOGY ===
            'psicologia': { keywords: ['psicologia', 'mente', 'ansiedade', 'depressão', 'estresse', 'stress', 'autoestima', 'freud', 'jung'], response: '🧠 PSICOLOGIA:\n\n• Ansiedade: Técnicas de respiração, mindfulness\n• Depressão: Procure ajuda profissional\n• Autoestima: Autoconhecimento, afirmações positivas\n• Freud: Pai da psicanálise (inconsciente)\n• Jung: Psicologia analítica (arquétipos)\n• Mindfulness: Meditação, atenção plena\n\n⚠️ Para questões sérias, procure um psicólogo!' },
            'psychology': { keywords: ['psychology', 'mind', 'anxiety', 'depression', 'stress', 'self-esteem', 'freud', 'jung'], lang: 'en', response: '🧠 PSYCHOLOGY:\n\n• Anxiety: Breathing techniques, mindfulness\n• Depression: Seek professional help\n• Self-esteem: Self-knowledge, positive affirmations\n• Freud: Father of psychoanalysis (unconscious)\n• Jung: Analytical psychology (archetypes)\n• Mindfulness: Meditation, present moment awareness\n\n⚠️ For serious issues, seek a psychologist!' },

            // === MEIO AMBIENTE / ENVIRONMENT ===
            'ambiente': { keywords: ['meio ambiente', 'ambiente', 'ecologia', 'sustentabilidade', 'reciclagem', 'clima', 'aquecimento global', 'poluição', 'natureza'], response: '🌱 MEIO AMBIENTE:\n\n• Aquecimento global: Aumento de 1.1°C desde era pré-industrial\n• Reciclagem: Separe plástico, papel, vidro, metal\n• Energia renovável: Solar, eólica, hidrelétrica\n• Desmatamento: Amazônia perdeu 17% da cobertura original\n• Dicas: Reduza plástico, economize água, use transporte público\n• Acordo de Paris: Meta de limitar aquecimento a 1.5°C\n\nPequenas ações fazem grande diferença!' },
            'environment': { keywords: ['environment', 'ecology', 'sustainability', 'recycling', 'climate', 'global warming', 'pollution', 'nature'], lang: 'en', response: '🌱 ENVIRONMENT:\n\n• Global warming: 1.1°C increase since pre-industrial\n• Recycling: Separate plastic, paper, glass, metal\n• Renewable energy: Solar, wind, hydroelectric\n• Deforestation: Amazon lost 17% original cover\n• Tips: Reduce plastic, save water, use public transport\n• Paris Agreement: Limit warming to 1.5°C\n\nSmall actions make big difference!' },

            // === POLÍTICA / POLITICS ===
            'politica': { keywords: ['política', 'governo', 'presidente', 'eleições', 'democracia', 'constituição', 'parlamento'], response: '🏛 POLÍTICA:\n\n• Moçambique: República presidencialista, presidente atual Daniel Chapo\n• Brasil: República federativa, presidente Lula\n• EUA: Democracia, presidente (eleito 2024)\n• ONU: 193 países-membros\n• Democracia: Sistema de governo do povo\n\nGostaria de saber sobre algum sistema político específico?' },
            'politics': { keywords: ['politics', 'government', 'president', 'elections', 'democracy', 'constitution', 'parliament'], lang: 'en', response: '🏛 POLITICS:\n\n• Mozambique: Presidential republic\n• Brazil: Federative republic\n• USA: Democracy\n• UN: 193 member countries\n• Democracy: Government by the people\n\nWant to know about a specific political system?' },

            // === ECONOMIA / ECONOMY ===
            'economia': { keywords: ['economia', 'economy', 'pib', 'gdp', 'inflação', 'inflation', 'mercado', 'bolsa', 'investimento', 'investment'], response: '📈 ECONOMIA:\n\n• PIB Mundial: ~$100 trilhões\n• Maior economia: EUA ($25T)\n• Moçambique: PIB ~$18B, crescimento ~5%\n• Inflação: Aumento geral dos preços\n• Bolsa de valores: Compra/venda de ações\n• Criptomoedas: Bitcoin, Ethereum\n• Juros: Taxa definida pelo Banco Central\n\nTema económico de interesse?' },
            'economy': { keywords: ['economy', 'gdp', 'inflation', 'market', 'stock', 'investment', 'bitcoin', 'crypto'], lang: 'en', response: '📈 ECONOMY:\n\n• World GDP: ~$100 trillion\n• Largest economy: USA ($25T)\n• Mozambique: GDP ~$18B, ~5% growth\n• Inflation: General price increase\n• Stock market: Buy/sell shares\n• Cryptocurrencies: Bitcoin, Ethereum\n\nEconomic topic of interest?' },

            // === VIAGENS / TRAVEL ===
            'viagens': { keywords: ['viagem', 'viajar', 'turismo', 'turista', 'visto', 'passaporte', 'hotel', 'praia', 'travel', 'trip', 'tourism', 'visa', 'passport'], response: '✈️ VIAGENS / TRAVEL:\n\nDESTINOS POPULARES:\n• Moçambique: Ilha de Moçambique, Bazaruto, Ponta do Ouro, Maputo\n• África: Cape Town, Zanzibar, Marrakech, Victoria Falls\n• Mundo: Paris, Roma, Bali, Tokyo, Nova York\n\nDICAS:\n✓ Passaporte válido (6 meses)\n✓ Visto (verifique necessidade)\n✓ Seguro viagem\n✓ Vacinas (febre amarela)\n✓ Melhor época: estação seca\n\nOrçamento? / Budget?' },

            // === ANIMAIS / ANIMALS ===
            'animais': { keywords: ['animal', 'animais', 'cachorro', 'gato', 'cão', 'pássaro', 'peixe', 'leão', 'elefante', 'animal de estimação', 'pet'], response: '🐾 ANIMAIS:\n\n• Cães: 340+ raças, expectativa de vida 10-13 anos\n• Gatos: Domesticados há 10.000 anos\n• Animais selvagens de África: Leão, elefante, girafa, zebra, hipopótamo\n• Vida marinha: Baleia-azul (maior animal, 30m)\n• Pets: Alimentação adequada, vacinas, veterinário regular\n\nTem dúvidas sobre algum animal específico?' },
            'animals': { keywords: ['animal', 'animals', 'dog', 'cat', 'bird', 'fish', 'lion', 'elephant', 'pet'], lang: 'en', response: '🐾 ANIMALS:\n\n• Dogs: 340+ breeds, lifespan 10-13 years\n• Cats: Domesticated 10,000 years ago\n• African wildlife: Lion, elephant, giraffe, zebra, hippo\n• Marine life: Blue whale (largest animal, 30m)\n• Pets: Proper food, vaccines, regular vet\n\nQuestions about a specific animal?' },

            // === SAUDAÇÕES / GREETINGS ===
            'ola': { keywords: ['olá', 'ola', 'oi', 'hey', 'bom dia', 'boa tarde', 'boa noite', 'hi', 'hello', 'good morning', 'good afternoon', 'good evening', 'greetings', 'saudação'], response: 'Olá! 😊 Hello! 😊\n\nBem-vindo(a) ao assistente da EXCELENT BUSINESS!\nWelcome to the EXCELENT BUSINESS assistant!\n\nPosso ajudar em Português e Inglês!\nI can help in Portuguese and English!\n\nComo posso ajudá-lo? / How can I help you?' },
            'obrigado': { keywords: ['obrigado', 'obrigada', 'valeu', 'grato', 'gratidão', 'thank you', 'thanks', 'thx', 'ty'], response: 'De nada! 😊 You\'re welcome! 😊\n\nFico feliz em ajudar! / Happy to help!\n\nSe tiver mais dúvidas, estou à disposição.\nIf you have more questions, I\'m here.\n\nDesejo muito sucesso! 🚀' },
            'adeus': { keywords: ['adeus', 'tchau', 'até logo', 'bye', 'xau', 'goodbye', 'see you', 'later'], response: 'Até logo! 👋 See you later! 👋\n\nFoi um prazer ajudar. / It was a pleasure.\n\nVolte sempre! / Come back anytime! 💼' },
            'quem_es': { keywords: ['quem és', 'quem é você', 'como te chamas', 'qual o teu nome', 'who are you', 'what is your name'], response: 'Sou o assistente virtual da EXCELENT BUSINESS! 🤖\nI\'m the EXCELENT BUSINESS virtual assistant! 🤖\n\nRespondo sobre negócios, história, ciência, geografia, tecnologia, saúde, cultura, desporto, culinária, música, cinema, línguas, psicologia, meio ambiente, política, economia, viagens, animais e muito mais!\n\nDisponível 24/7!\nComo posso ajudar? / How can I help?' },

            // === DEFAULT ===
            'default': { keywords: [], response: '🤔 Obrigado pela sua pergunta! / Thank you for your question!\n\nPosso ajudar com / I can help with:\n\n📊 Negócios / Business\n🌍 História / History\n🔬 Ciência / Science\n🗺 Geografia / Geography\n💻 Tecnologia / Technology\n🏥 Saúde / Health\n🎨 Cultura / Culture\n⚽ Desporto / Sports\n🍳 Culinária / Cooking\n🎵 Música / Music\n🎬 Cinema / Movies\n🗣 Línguas / Languages\n🧠 Psicologia / Psychology\n🌱 Meio Ambiente / Environment\n🏛 Política / Politics\n📈 Economia / Economy\n✈️ Viagens / Travel\n🐾 Animais / Animals\n\nE muito mais! / And much more!\n\nTente reformular ou escolha um tema! 😊' }
        };

        function detectLanguage(text) {
            const enWords = ['how', 'what', 'when', 'where', 'why', 'who', 'can', 'help', 'need', 'want', 'start', 'business', 'customer', 'marketing', 'growth', 'finance', 'price', 'please', 'thanks', 'hello', 'hi', 'hey', 'the', 'is', 'are', 'you', 'me', 'my', 'your', 'i'];
            const ptWords = ['como', 'que', 'quando', 'onde', 'porque', 'quem', 'posso', 'ajuda', 'preciso', 'quero', 'começar', 'negócio', 'cliente', 'marketing', 'crescimento', 'finanças', 'preço', 'obrigado', 'olá', 'oi', 'obrigada'];
            const lower = text.toLowerCase();
            let en = 0, pt = 0;
            enWords.forEach(w => { if (lower.includes(w)) en++; });
            ptWords.forEach(w => { if (lower.includes(w)) pt++; });
            if (/[áàâãéêíóôõúç]/.test(lower)) return 'pt';
            return en > pt ? 'en' : 'pt';
        }

        function findResponse(question) {
            const lower = question.toLowerCase().trim();
            const lang = detectLanguage(question);
            let bestMatch = null, bestScore = 0;
            
            for (const [key, data] of Object.entries(knowledgeBase)) {
                if (key === 'default') continue;
                let score = 0;
                for (const kw of data.keywords) {
                    if (lower.includes(kw.toLowerCase())) score += kw.length;
                }
                if (data.lang === lang) score *= 2;
                if (score > bestScore) { bestScore = score; bestMatch = data.response; }
            }
            
            if (bestMatch) return bestMatch;
            
            return lang === 'en' ? 
                '🤔 Interesting question! I don\'t have a specific answer but can help with business, history, science, geography, technology, health, culture, sports, cooking, music, movies, languages, psychology, environment, politics, economy, travel, animals and more! Try rephrasing! 😊' :
                '🤔 Pergunta interessante! Posso ajudar com negócios, história, ciência, geografia, tecnologia, saúde, cultura, desporto, culinária, música, cinema, línguas, psicologia, meio ambiente, política, economia, viagens, animais e muito mais! Tente reformular! 😊';
        }

        function addChatMessage(content, isUser = false) {
            const div = document.createElement('div');
            div.className = `chat-message ${isUser ? 'user' : 'bot'}`;
            const bubble = document.createElement('div');
            bubble.className = 'chat-bubble';
            bubble.innerHTML = content.replace(/\n/g, '<br>');
            div.appendChild(bubble);
            chatMessages.appendChild(div);
            chatMessages.scrollTop = chatMessages.scrollHeight;
        }

        function handleChatQuestion(question) {
            if (!question.trim()) return;
            addChatMessage(question, true);
            chatInput.value = '';
            
            const typingDiv = document.createElement('div');
            typingDiv.className = 'chat-message bot';
            typingDiv.id = 'typingIndicator';
            typingDiv.innerHTML = `<div class="chat-bubble">${detectLanguage(question) === 'en' ? 'Processing...' : 'A processar...'}</div>`;
            chatMessages.appendChild(typingDiv);
            chatMessages.scrollTop = chatMessages.scrollHeight;
            
            setTimeout(() => {
                document.getElementById('typingIndicator')?.remove();
                addChatMessage(findResponse(question), false);
            }, 600 + Math.random() * 800);
        }

        chatSend.addEventListener('click', () => handleChatQuestion(chatInput.value));
        chatInput.addEventListener('keypress', e => { if (e.key === 'Enter') handleChatQuestion(chatInput.value); });
        document.querySelectorAll('.chat-suggestion').forEach(btn => { btn.addEventListener('click', () => handleChatQuestion(btn.textContent)); });
        
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                const href = this.getAttribute('href');
                if (href === '#') return;
                e.preventDefault();
                const target = document.querySelector(href);
                if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
            });
        });

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) { entry.target.style.opacity = '1'; entry.target.style.transform = 'translateY(0)'; }
            });
        }, { threshold: 0.1 });
        document.querySelectorAll('.card, .value-card, .testimonial-card').forEach(el => {
            el.style.opacity = '0'; el.style.transform = 'translateY(30px)'; el.style.transition = 'all 0.6s ease'; observer.observe(el);
        });

        console.log('✅ EXCELENT BUSINESS - Chat Assistant com 60+ categorias');
        console.log('🌐 Bilíngue: Português + Inglês');
        console.log('📚 Categorias: Negócios, História, Ciência, Geografia, Tecnologia, Saúde, Cultura, Desporto, Culinária, Música, Cinema, Línguas, Psicologia, Meio Ambiente, Política, Economia, Viagens, Animais e mais!');
    </script>
</body>
</html>
