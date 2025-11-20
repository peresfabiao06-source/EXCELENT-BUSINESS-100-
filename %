<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EXCELENT BUSINESS - Transforme Ideias em Negócios de Sucesso</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            overflow-x: hidden;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes slideInLeft {
            from {
                opacity: 0;
                transform: translateX(-50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
        }

        @keyframes gradientShift {
            0% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0% 50%;
            }
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0px);
            }
            50% {
                transform: translateY(-20px);
            }
        }

        header {
            background: linear-gradient(135deg, #0f2027 0%, #203a43 50%, #2c5364 100%);
            color: white;
            padding: 1.5rem 0;
            box-shadow: 0 4px 20px rgba(0,0,0,0.3);
            position: sticky;
            top: 0;
            z-index: 1000;
            backdrop-filter: blur(10px);
            transition: all 0.3s ease;
        }

        nav {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 2rem;
            animation: fadeInUp 0.8s ease;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            transition: transform 0.3s ease;
        }

        .logo:hover {
            transform: scale(1.05);
        }

        .logo-icon {
            font-size: 2rem;
            animation: pulse 2s ease-in-out infinite;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            transition: all 0.3s;
            position: relative;
            padding: 0.5rem 0;
            font-weight: 500;
            font-size: 0.95rem;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: linear-gradient(90deg, #667eea, #764ba2);
            transition: width 0.3s ease;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .nav-links a:hover {
            color: #667eea;
        }

        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            background-size: 200% 200%;
            animation: gradientShift 15s ease infinite;
            color: white;
            padding: 8rem 2rem;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg"><circle cx="50" cy="50" r="2" fill="rgba(255,255,255,0.1)"/></svg>');
            animation: float 20s linear infinite;
        }

        .hero-content {
            position: relative;
            z-index: 1;
            animation: fadeInUp 1s ease;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1.5rem;
            font-weight: 700;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            animation: slideInLeft 1s ease;
        }

        .hero p {
            font-size: 1.3rem;
            max-width: 900px;
            margin: 0 auto 2rem;
            animation: fadeInUp 1.2s ease;
            line-height: 1.8;
        }

        .cta-button {
            display: inline-block;
            padding: 1rem 2.5rem;
            background: white;
            color: #667eea;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            animation: fadeInUp 1.4s ease;
            margin: 0.5rem;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 25px rgba(0,0,0,0.3);
            background: #f0f0f0;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 5rem 2rem;
        }

        .section {
            margin-bottom: 5rem;
            animation: fadeInUp 0.8s ease;
        }

        .section h2 {
            font-size: 2.8rem;
            color: #0f2027;
            margin-bottom: 2rem;
            border-left: 6px solid #667eea;
            padding-left: 1.5rem;
            position: relative;
            animation: slideInLeft 0.8s ease;
        }

        .section h2::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: -10px;
            width: 100px;
            height: 3px;
            background: linear-gradient(90deg, #667eea, #764ba2);
        }

        .section p {
            font-size: 1.15rem;
            margin-bottom: 1.5rem;
            line-height: 1.8;
            color: #555;
        }

        .beliefs {
            background: #f8f9fa;
            padding: 2rem;
            border-radius: 15px;
            margin: 2rem 0;
        }

        .beliefs ul {
            list-style: none;
            padding-left: 0;
        }

        .beliefs li {
            padding: 1rem 0;
            padding-left: 2rem;
            position: relative;
            font-size: 1.1rem;
        }

        .beliefs li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: #667eea;
            font-weight: bold;
            font-size: 1.5rem;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2.5rem;
            margin-top: 3rem;
        }

        .card {
            background: white;
            padding: 2.5rem;
            border-radius: 15px;
            box-shadow: 0 5px 25px rgba(0,0,0,0.08);
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(102, 126, 234, 0.1);
        }

        .card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: linear-gradient(90deg, #667eea, #764ba2);
            transform: scaleX(0);
            transition: transform 0.4s ease;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(102, 126, 234, 0.3);
        }

        .card:hover::before {
            transform: scaleX(1);
        }

        .card h3 {
            color: #667eea;
            font-size: 1.6rem;
            margin-bottom: 1rem;
            font-weight: 600;
        }

        .card p {
            color: #666;
            line-height: 1.7;
        }

        .card-icon {
            font-size: 3.5rem;
            margin-bottom: 1.5rem;
            display: inline-block;
            transition: transform 0.3s ease;
        }

        .card:hover .card-icon {
            transform: scale(1.2) rotate(5deg);
        }

        .target-audience {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .audience-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
            transition: all 0.3s ease;
        }

        .audience-card:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.4);
        }

        .audience-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .services {
            background: #f8f9fa;
            padding: 2rem;
            border-radius: 15px;
        }

        .services ul {
            list-style: none;
            padding: 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }

        .services li {
            padding: 1rem;
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            transition: all 0.3s ease;
        }

        .services li:hover {
            transform: translateX(10px);
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.2);
        }

        .testimonials {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 4rem 2rem;
            border-radius: 20px;
            color: white;
            margin: 3rem 0;
        }

        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .testimonial {
            background: rgba(255,255,255,0.1);
            padding: 2rem;
            border-radius: 15px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.2);
        }

        .testimonial p {
            font-style: italic;
            margin-bottom: 1rem;
            font-size: 1.1rem;
        }

        .testimonial-author {
            font-weight: bold;
            text-align: right;
        }

        .mvv-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .mvv-card {
            background: white;
            padding: 2.5rem;
            border-radius: 15px;
            box-shadow: 0 5px 25px rgba(0,0,0,0.08);
            border-top: 5px solid #667eea;
        }

        .mvv-card h3 {
            color: #667eea;
            font-size: 1.8rem;
            margin-bottom: 1rem;
        }

        .values-list {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }

        .value-tag {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 0.5rem 1.5rem;
            border-radius: 25px;
            font-weight: 500;
        }

        .contact-section {
            background: #f8f9fa;
            padding: 3rem;
            border-radius: 20px;
            text-align: center;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 2rem;
            flex-wrap: wrap;
        }

        .contact-btn {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            padding: 1rem 2rem;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.3);
        }

        .contact-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 25px rgba(102, 126, 234, 0.5);
        }

        footer {
            background: #0f2027;
            color: white;
            text-align: center;
            padding: 3rem 2rem;
            position: relative;
        }

        footer p {
            margin: 0.5rem 0;
            opacity: 0.8;
        }

        .scroll-indicator {
            position: absolute;
            bottom: 2rem;
            left: 50%;
            transform: translateX(-50%);
            animation: float 2s ease-in-out infinite;
        }

        .scroll-indicator::before {
            content: '↓';
            font-size: 2rem;
            color: white;
        }

        /* Chat Assistant Styles */
        .chat-button {
            position: fixed;
            bottom: 2rem;
            right: 2rem;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            font-size: 1.8rem;
            cursor: pointer;
            box-shadow: 0 4px 20px rgba(102, 126, 234, 0.4);
            transition: all 0.3s ease;
            z-index: 1000;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .chat-button:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 30px rgba(102, 126, 234, 0.6);
        }

        .chat-window {
            position: fixed;
            bottom: 5rem;
            right: 2rem;
            width: 380px;
            height: 550px;
            background: white;
            border-radius: 20px;
            box-shadow: 0 10px 40px rgba(0,0,0,0.3);
            display: none;
            flex-direction: column;
            z-index: 999;
            overflow: hidden;
            animation: slideUp 0.3s ease;
        }

        .chat-window.active {
            display: flex;
        }

        @keyframes slideUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .chat-header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1.5rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .chat-header h3 {
            margin: 0;
            font-size: 1.2rem;
        }

        .chat-close {
            background: none;
            border: none;
            color: white;
            font-size: 1.5rem;
            cursor: pointer;
            transition: transform 0.2s;
        }

        .chat-close:hover {
            transform: rotate(90deg);
        }

        .chat-messages {
            flex: 1;
            padding: 1.5rem;
            overflow-y: auto;
            background: #f8f9fa;
        }

        .message {
            margin-bottom: 1rem;
            display: flex;
            gap: 0.5rem;
            animation: fadeInUp 0.3s ease;
        }

        .message.bot {
            justify-content: flex-start;
        }

        .message.user {
            justify-content: flex-end;
        }

        .message-content {
            max-width: 75%;
            padding: 0.8rem 1rem;
            border-radius: 15px;
            line-height: 1.5;
        }

        .message.bot .message-content {
            background: white;
            color: #333;
            border: 1px solid #e0e0e0;
        }

        .message.user .message-content {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }

        .chat-suggestions {
            padding: 0.5rem 1rem;
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            background: #f8f9fa;
        }

        .suggestion-btn {
            padding: 0.5rem 1rem;
            background: white;
            border: 1px solid #667eea;
            color: #667eea;
            border-radius: 20px;
            font-size: 0.85rem;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .suggestion-btn:hover {
            background: #667eea;
            color: white;
        }

        .chat-input-area {
            padding: 1rem;
            background: white;
            border-top: 1px solid #e0e0e0;
            display: flex;
            gap: 0.5rem;
        }

        .chat-input {
            flex: 1;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 25px;
            outline: none;
            font-size: 0.95rem;
        }

        .chat-input:focus {
            border-color: #667eea;
        }

        .chat-send {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            cursor: pointer;
            font-size: 1.2rem;
            transition: all 0.3s ease;
        }

        .chat-send:hover {
            transform: scale(1.1);
        }

        .typing-indicator {
            display: none;
            padding: 0.8rem 1rem;
            background: white;
            border-radius: 15px;
            width: fit-content;
            border: 1px solid #e0e0e0;
        }

        .typing-indicator.active {
            display: block;
        }

        .typing-indicator span {
            display: inline-block;
            width: 8px;
            height: 8px;
            border-radius: 50%;
            background: #667eea;
            margin: 0 2px;
            animation: typing 1.4s infinite;
        }

        .typing-indicator span:nth-child(2) {
            animation-delay: 0.2s;
        }

        .typing-indicator span:nth-child(3) {
            animation-delay: 0.4s;
        }

        @keyframes typing {
            0%, 60%, 100% {
                transform: translateY(0);
            }
            30% {
                transform: translateY(-10px);
            }
        }

        @media (max-width: 768px) {
            .chat-window {
                width: calc(100% - 2rem);
                right: 1rem;
                left: 1rem;
                height: 70vh;
            }

            .chat-button {
                bottom: 1rem;
                right: 1rem;
            }
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.2rem;
            }

            .hero p {
                font-size: 1.1rem;
            }

            .nav-links {
                display: none;
            }

            .section h2 {
                font-size: 2rem;
            }

            .cards {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <span class="logo-icon">💼</span>
                <span>EXCELENT BUSINESS</span>
            </div>
            <ul class="nav-links">
                <li><a href="#sobre">Sobre Nós</a></li>
                <li><a href="#atendimento">Atendimento</a></li>
                <li><a href="#dicas">Dicas</a></li>
                <li><a href="#comeco">Como Começar</a></li>
                <li><a href="#crescimento">Crescimento</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Transforme Ideias em Negócios de Sucesso</h1>
            <p>Na EXCELENT BUSINESS, oferecemos dicas inteligentes, estratégias práticas e insights reais para ajudar empreendedores, gestores e empresas de todos os portes a alcançarem crescimento sustentável e resultados consistentes.</p>
            <a href="#sobre" class="cta-button">Descubra Mais →</a>
            <a href="#contacto" class="cta-button">Entre em Contacto</a>
        </div>
        <div class="scroll-indicator"></div>
    </section>

    <div class="container">
        <section id="sobre" class="section">
            <h2>📘 Sobre Nós</h2>
            <p>A EXCELENT BUSINESS é uma plataforma digital criada com o objetivo de democratizar o conhecimento empresarial, oferecendo conteúdos úteis e acessíveis para pequenos, médios e grandes negócios.</p>
            
            <div class="beliefs">
                <h3 style="color: #667eea; margin-bottom: 1rem;">Acreditamos que:</h3>
                <ul>
                    <li>Qualquer pessoa pode empreender, desde que tenha orientação certa.</li>
                    <li>O sucesso empresarial depende de planeamento, inovação e tomadas de decisão inteligentes.</li>
                    <li>O conhecimento deve ser acessível, prático e aplicável no dia a dia.</li>
                </ul>
            </div>

            <p>O nosso compromisso é fornecer informações claras, confiáveis e atualizadas sobre gestão, vendas, marketing, finanças e estratégia empresarial.</p>
        </section>

        <section id="dicas" class="section">
            <h2>💡 Dicas Inteligentes</h2>
            <p>Conteúdos práticos e aplicáveis para o sucesso do seu negócio:</p>
            
            <div class="cards">
                <div class="card">
                    <div class="card-icon">🌱</div>
                    <h3>Comece Pequeno, Cresça Inteligente</h3>
                    <p>Antes de expandir, garante que o teu modelo de negócios é sólido e escalável.</p>
                </div>
                <div class="card">
                    <div class="card-icon">⭐</div>
                    <h3>Investe na Experiência do Cliente</h3>
                    <p>Mais de 70% do sucesso de um negócio depende de como o cliente se sente ao interagir contigo.</p>
                </div>
                <div class="card">
                    <div class="card-icon">⚙️</div>
                    <h3>Automatize Processos</h3>
                    <p>Automação reduz custos, evita erros e aumenta a produtividade.</p>
                </div>
                <div class="card">
                    <div class="card-icon">💰</div>
                    <h3>Diversifique Fontes de Renda</h3>
                    <p>O futuro é incerto. Empresas inteligentes criam múltiplas formas de faturamento.</p>
                </div>
                <div class="card">
                    <div class="card-icon">📚</div>
                    <h3>Aprende com os Melhores</h3>
                    <p>Analise o que grandes empresas fazem e adapta à tua realidade.</p>
                </div>
                <div class="card">
                    <div class="card-icon">📱</div>
                    <h3>Marketing Digital Não é uma Opção — É Necessidade</h3>
                    <p>Divulga o teu negócio nas redes sociais, Google e WhatsApp Business.</p>
                </div>
            </div>
        </section>

        <section id="publico" class="section">
            <h2>📊 Para Quem é este Site?</h2>
            <p>A EXCELENT BUSINESS foi criada para:</p>
            
            <div class="target-audience">
                <div class="audience-card">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🏪</div>
                    <h3>Pequenas Empresas</h3>
                    <p>Empreendedores que precisam de direção prática e de baixo custo.</p>
                </div>
                <div class="audience-card">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🏢</div>
                    <h3>Médias Empresas</h3>
                    <p>Negócios em crescimento que precisam melhorar processos, marketing e finanças.</p>
                </div>
                <div class="audience-card">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🏛️</div>
                    <h3>Grandes Empresas</h3>
                    <p>Organizações que desejam inovação, transformação digital e estratégias avançadas.</p>
                </div>
                <div class="audience-card">
                    <div style="font-size: 3rem; margin-bottom: 1rem;">🚀</div>
                    <h3>Jovens Empreendedores</h3>
                    <p>Pessoas com ideias que querem iniciar um negócio com segurança.</p>
                </div>
            </div>
        </section>

        <section id="comeco" class="section">
            <h2>🚀 Como Começar um Negócio com Pouco Dinheiro</h2>
            <p>Não precisa de muito capital para começar! O importante é começar com o que tem e crescer de forma inteligente. Aqui estão as melhores estratégias:</p>
            
            <div class="cards">
                <div class="card">
                    <div class="card-icon">💡</div>
                    <h3>1. Identifique uma Necessidade Real</h3>
                    <p>Observe problemas ao seu redor que pode resolver. Converse com pessoas, identifique dores e transforme isso em oportunidade. O melhor negócio resolve um problema real.</p>
                </div>
                <div class="card">
                    <div class="card-icon">🏠</div>
                    <h3>2. Comece de Casa</h3>
                    <p>Evite custos de aluguer no início. Use a sua casa, garagem ou quintal. Muitas empresas de sucesso começaram em casa (Apple, Amazon, Facebook).</p>
                </div>
                <div class="card">
                    <div class="card-icon">📱</div>
                    <h3>3. Use Redes Sociais Gratuitas</h3>
                    <p>Facebook, Instagram, WhatsApp Business e TikTok são ferramentas gratuitas poderosas. Crie conteúdo de valor, mostre o seu trabalho e conecte-se com clientes.</p>
                </div>
                <div class="card">
                    <div class="card-icon">🤝</div>
                    <h3>4. Ofereça Serviços Antes de Produtos</h3>
                    <p>Serviços exigem pouco investimento inicial. Consultoria, design, limpeza, manutenção, ensino - use as suas habilidades para gerar receita imediata.</p>
                </div>
                <div class="card">
                    <div class="card-icon">♻️</div>
                    <h3>5. Reinvista os Lucros</h3>
                    <p>Nos primeiros meses, reinvista todo o lucro no negócio. Compre ferramentas, melhore o produto, invista em marketing. O crescimento vem do reinvestimento.</p>
                </div>
                <div class="card">
                    <div class="card-icon">🎯</div>
                    <h3>6. Foque num Nicho Específico</h3>
                    <p>Não tente vender para todos. Escolha um público específico e torne-se especialista nisso. É mais fácil dominar um pequeno mercado.</p>
                </div>
            </div>

            <div class="highlight-box" style="margin-top: 3rem; background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%); border-left: 5px solid #4caf50;">
                <h3 style="color: #2e7d32;">💰 Negócios para Começar com Menos de 5.000MT</h3>
                <div class="cards" style="margin-top: 2rem;">
                    <div style="background: white; padding: 1.5rem; border-radius: 10px;">
                        <strong>🍰 Venda de Bolos e Doces:</strong> Comece na cozinha de casa, use redes sociais para divulgar.
                    </div>
                    <div style="background: white; padding: 1.5rem; border-radius: 10px;">
                        <strong>🧼 Produtos de Limpeza:</strong> Faça sabão, detergentes caseiros e venda porta a porta.
                    </div>
                    <div style="background: white; padding: 1.5rem; border-radius: 10px;">
                        <strong>📱 Recarga de Telemóveis:</strong> Revenda créditos e serviços móveis.
                    </div>
                    <div style="background: white; padding: 1.5rem; border-radius: 10px;">
                        <strong>✂️ Cabeleireiro ao Domicílio:</strong> Atenda clientes em casa com equipamento básico.
                    </div>
                    <div style="background: white; padding: 1.5rem; border-radius: 10px;">
                        <strong>📚 Explicações:</strong> Ensine o que sabe (línguas, matemática, informática).
                    </div>
                    <div style="background: white; padding: 1.5rem; border-radius: 10px;">
                        <strong>🌱 Horta Urbana:</strong> Cultive vegetais orgânicos no quintal e venda fresco.
                    </div>
                </div>
            </div>
        </section>

        <section id="atendimento" class="section">
            <h2>⭐ Atendimento ao Cliente: O Pilar do Sucesso</h2>
            <p><strong>O cliente é a razão da existência do seu negócio.</strong> Um atendimento excepcional não é um diferencial — é uma necessidade absoluta. Clientes bem atendidos voltam, recomendam e defendem a sua marca.</p>
            
            <div class="highlight-box" style="background: linear-gradient(135deg, #fff8e1 0%, #ffe082 100%); border-left: 5px solid #ffa000;">
                <h3 style="color: #f57c00;">🔥 A Verdade Brutal sobre Atendimento</h3>
                <p style="font-size: 1.15rem; line-height: 1.8;"><strong>Um cliente mal atendido pode destruir o seu negócio.</strong> Estudos mostram que:</p>
                <ul style="margin-top: 1rem; padding-left: 2rem;">
                    <li style="margin: 0.5rem 0;">Um cliente satisfeito conta a 3 pessoas sobre a experiência</li>
                    <li style="margin: 0.5rem 0;">Um cliente INSATISFEITO conta a 15 pessoas ou mais</li>
                    <li style="margin: 0.5rem 0;">96% dos clientes insatisfeitos não reclamam — simplesmente não voltam</li>
                    <li style="margin: 0.5rem 0;">Conquistar um novo cliente custa 5x mais do que manter um existente</li>
                </ul>
                <p style="margin-top: 1rem; font-weight: bold; color: #e65100;">❌ Conclusão: Você NÃO pode dar-se ao luxo de ter um mau atendimento!</p>
            </div>

            <h3 style="font-size: 2rem; color: #667eea; margin-top: 3rem; margin-bottom: 2rem;">🎯 Princípios de Atendimento Excepcional</h3>

            <div class="cards">
                <div class="card">
                    <div class="card-icon">👂</div>
                    <h3>1. Escute Ativamente</h3>
                    <p><strong>Não apenas ouça, COMPREENDA.</strong><br>
                    ✓ Mantenha contacto visual<br>
                    ✓ Faça perguntas de esclarecimento<br>
                    ✓ Repita para confirmar que entendeu<br>
                    ✓ Mostre empatia genuína<br>
                    <em>"O cliente não quer ser ouvido, quer ser compreendido."</em></p>
                </div>
                <div class="card">
                    <div class="card-icon">⚡</div>
                    <h3>2. Agilidade é Ouro</h3>
                    <p><strong>Tempo é o ativo mais valioso do cliente.</strong><br>
                    ✓ Responda mensagens em menos de 2 horas<br>
                    ✓ Atenda chamadas até o 3º toque<br>
                    ✓ Resolva problemas no primeiro contacto<br>
                    ✓ Se não puder resolver imediatamente, dê prazo realista<br>
                    <em>"Cliente que espera é cliente que está a procurar alternativas."</em></p>
                </div>
                <div class="card">
                    <div class="card-icon">😊</div>
                    <h3>3. Atitude Positiva Sempre</h3>
                    <p><strong>Mesmo em dias ruins, o cliente não pode perceber.</strong><br>
                    ✓ Sorria (mesmo ao telefone, nota-se!)<br>
                    ✓ Use linguagem positiva<br>
                    ✓ Nunca diga "não posso", diga "vou verificar como posso ajudar"<br>
                    ✓ Trate reclamações como oportunidades de melhorar<br>
                    <em>"O seu humor não é problema do cliente."</em></p>
                </div>
                <div class="card">
                    <div class="card-icon">🎁</div>
                    <h3>4. Supere Expectativas</h3>
                    <p><strong>Faça mais do que o esperado.</strong><br>
                    ✓ Pequenos gestos fazem grande diferença<br>
                    ✓ Lembre-se de aniversários ou datas importantes<br>
                    ✓ Ofereça algo extra sem ser pedido<br>
                    ✓ Personalize o atendimento<br>
                    <em>"Clientes esperam bom serviço. Surpreenda-os com excepcional."</em></p>
                </div>
                <div class="card">
                    <div class="card-icon">🔧</div>
                    <h3>5. Resolução de Problemas</h3>
                    <p><strong>Erros acontecem. A diferença está em como os resolve.</strong><br>
                    ✓ Assuma a responsabilidade imediatamente<br>
                    ✓ Peça desculpas sinceramente<br>
                    ✓ Apresente solução concreta<br>
                    ✓ Acompanhe até garantir satisfação<br>
                    <em>"Um problema bem resolvido cria mais lealdade que nunca ter tido problema."</em></p>
                </div>
                <div class="card">
                    <div class="card-icon">💬</div>
                    <h3>6. Comunicação Clara</h3>
                    <p><strong>Evite mal-entendidos a todo custo.</strong><br>
                    ✓ Seja claro e directo<br>
                    ✓ Confirme informações importantes por escrito<br>
                    ✓ Use linguagem que o cliente entenda (sem jargões)<br>
                    ✓ Informe proativamente sobre mudanças<br>
                    <em>"Comunicação clara = Cliente confiante."</em></p>
                </div>
            </div>

            <div class="testimonials" style="margin-top: 3rem; background: linear-gradient(135deg, #e53935 0%, #c62828 100%);">
                <h3 style="font-size: 2rem; margin-bottom: 1rem;">⚠️ Erros Fatais no Atendimento (EVITE!)</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5rem; margin-top: 2rem;">
                    <div style="background: rgba(255,255,255,0.15); padding: 1.5rem; border-radius: 10px;">
                        <strong>❌ Ignorar o Cliente</strong><br>
                        <small>Deixar mensagens sem resposta ou fazer o cliente esperar sem explicação</small>
                    </div>
                    <div style="background: rgba(255,255,255,0.15); padding: 1.5rem; border-radius: 10px;">
                        <strong>❌ Discutir ou Confrontar</strong><br>
                        <small>O cliente nem sempre tem razão, mas sempre merece respeito</small>
                    </div>
                    <div style="background: rgba(255,255,255,0.15); padding: 1.5rem; border-radius: 10px;">
                        <strong>❌ Prometer e Não Cumprir</strong><br>
                        <small>Melhor prometer menos e entregar mais que o contrário</small>
                    </div>
                    <div style="background: rgba(255,255,255,0.15); padding: 1.5rem; border-radius: 10px;">
                        <strong>❌ Transferir Responsabilidade</strong><br>
                        <small>"Não é comigo" ou "Fale com o gerente" frustra o cliente</small>
                    </div>
                    <div style="background: rgba(255,255,255,0.15); padding: 1.5rem; border-radius: 10px;">
                        <strong>❌ Ser Frio ou Robótico</strong><br>
                        <small>Clientes querem interagir com humanos, não máquinas</small>
                    </div>
                    <div style="background: rgba(255,255,255,0.15); padding: 1.5rem; border-radius: 10px;">
                        <strong>❌ Não Pedir Feedback</strong><br>
                        <small>Como vai melhorar se não sabe o que está errado?</small>
                    </div>
                </div>
            </div>

            <div style="background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%); padding: 3rem; border-radius: 20px; margin-top: 3rem; border-left: 6px solid #4caf50;">
                <h3 style="color: #2e7d32; font-size: 2rem; margin-bottom: 2rem;">✅ Checklist Diária de Atendimento</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem;">
                    <div style="background: white; padding: 1.5rem; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.05);">
                        <strong style="color: #667eea;">📱 Manhã (8h-12h)</strong><br>
                        □ Verificar todas as mensagens<br>
                        □ Responder pedidos pendentes<br>
                        □ Confirmar entregas do dia<br>
                        □ Preparar-se mentalmente para atender bem
                    </div>
                    <div style="background: white; padding: 1.5rem; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.05);">
                        <strong style="color: #667eea;">☀️ Tarde (12h-18h)</strong><br>
                        □ Acompanhar satisfação dos clientes<br>
                        □ Resolver problemas urgentes<br>
                        □ Actualizar status de pedidos<br>
                        □ Responder dúvidas rapidamente
                    </div>
                    <div style="background: white; padding: 1.5rem; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.05);">
                        <strong style="color: #667eea;">🌙 Noite (18h-22h)</strong><br>
                        □ Última verificação de mensagens<br>
                        □ Agradecer clientes do dia<br>
                        □ Planear atendimentos de amanhã<br>
                        □ Avaliar: o que posso melhorar?
                    </div>
                </div>
            </div>

            <div style="margin-top: 3rem; text-align: center; padding: 2rem; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; border-radius: 15px;">
                <h3 style="font-size: 2rem; margin-bottom: 1rem;">💎 A Regra de Ouro</h3>
                <p style="font-size: 1.3rem; font-weight: bold; margin-bottom: 1rem;">"Trate cada cliente como gostaria de ser tratado"</p>
                <p style="font-size: 1.1rem;">Atendimento excepcional não é sorte — é escolha. É treinamento. É compromisso diário. É colocar o cliente no centro de TUDO o que faz. Empresas crescem ou morrem pela qualidade do atendimento.</p>
            </div>
        </section>

        <section id="crescimento" class="section">
            <h2>📈 Estratégias de Crescimento Sustentável</h2>
            <p>Depois de começar, use estas estratégias comprovadas para fazer o seu negócio crescer:</p>

            <div class="cards">
                <div class="card">
                    <div class="card-icon">👥</div>
                    <h3>Construa uma Base de Clientes Fiéis</h3>
                    <p><strong>Passo 1:</strong> Trate cada cliente como único. Lembre-se dos nomes, preferências e histórias.<br>
                    <strong>Passo 2:</strong> Crie um programa de fidelidade simples (desconto na 5ª compra).<br>
                    <strong>Passo 3:</strong> Peça feedback e implemente sugestões.</p>
                </div>
                <div class="card">
                    <div class="card-icon">🎁</div>
                    <h3>Marketing Boca a Boca</h3>
                    <p><strong>Ofereça algo extraordinário:</strong> Surpreenda clientes com qualidade excepcional.<br>
                    <strong>Incentive referências:</strong> "Traga um amigo e ambos ganham 10% desconto".<br>
                    <strong>Peça avaliações:</strong> Reviews positivas atraem novos clientes.</p>
                </div>
                <div class="card">
                    <div class="card-icon">📊</div>
                    <h3>Controle Rigoroso de Finanças</h3>
                    <p><strong>Registe tudo:</strong> Cada entrada e saída de dinheiro (use caderno ou Excel).<br>
                    <strong>Separe o pessoal do empresarial:</strong> Nunca misture as contas.<br>
                    <strong>Analise mensalmente:</strong> Quais produtos dão mais lucro? Onde pode cortar custos?</p>
                </div>
                <div class="card">
                    <div class="card-icon">🔄</div>
                    <h3>Diversifique Produtos/Serviços</h3>
                    <p><strong>Escute o cliente:</strong> O que mais eles precisam?<br>
                    <strong>Adicione complementos:</strong> Se vende bolos, adicione salgados.<br>
                    <strong>Crie pacotes:</strong> Combine produtos para aumentar ticket médio.</p>
                </div>
                <div class="card">
                    <div class="card-icon">🤖</div>
                    <h3>Automatize e Sistematize</h3>
                    <p><strong>Crie processos:</strong> Escreva passo a passo de cada tarefa.<br>
                    <strong>Use ferramentas gratuitas:</strong> Google Sheets, WhatsApp Business, Trello.<br>
                    <strong>Organize o tempo:</strong> Reserve horários específicos para cada atividade.</p>
                </div>
                <div class="card">
                    <div class="card-icon">🎓</div>
                    <h3>Nunca Pare de Aprender</h3>
                    <p><strong>Acompanhe concorrentes:</strong> O que fazem bem? Como pode adaptar?<br>
                    <strong>Consuma conteúdo:</strong> YouTube, podcasts, blogs sobre o seu setor.<br>
                    <strong>Networking:</strong> Conecte-se com outros empreendedores, troque experiências.</p>
                </div>
            </div>

            <div class="testimonials" style="margin-top: 3rem;">
                <h3 style="font-size: 2rem; margin-bottom: 1rem;">🎯 Plano de Crescimento em 12 Meses</h3>
                <div style="background: rgba(255,255,255,0.1); padding: 2rem; border-radius: 15px; text-align: left;">
                    <p><strong>Mês 1-3: FUNDAÇÃO</strong><br>
                    ✓ Valide a ideia com clientes reais<br>
                    ✓ Ajuste produto/serviço baseado em feedback<br>
                    ✓ Crie presença nas redes sociais<br>
                    ✓ Reinvista 100% do lucro</p>
                    
                    <p style="margin-top: 1.5rem;"><strong>Mês 4-6: EXPANSÃO CONTROLADA</strong><br>
                    ✓ Aumente produção gradualmente<br>
                    ✓ Invista em marketing (panfletos, anúncios online)<br>
                    ✓ Melhore processos e qualidade<br>
                    ✓ Comece a formar pequena reserva financeira</p>
                    
                    <p style="margin-top: 1.5rem;"><strong>Mês 7-9: PROFISSIONALIZAÇÃO</strong><br>
                    ✓ Formalize o negócio (se ainda não fez)<br>
                    ✓ Contrate primeira ajuda (se necessário)<br>
                    ✓ Diversifique produtos/serviços<br>
                    ✓ Estabeleça parcerias estratégicas</p>
                    
                    <p style="margin-top: 1.5rem;"><strong>Mês 10-12: CONSOLIDAÇÃO</strong><br>
                    ✓ Analise resultados do ano<br>
                    ✓ Identifique pontos fortes e fracos<br>
                    ✓ Planeie próximo ano com metas claras<br>
                    ✓ Considere expansão ou novo nicho</p>
                </div>
            </div>
        </section>

        <section id="servicos" class="section">
            <h2>🛠 Serviços Futuramente Disponíveis</h2>
            <div class="services">
                <ul>
                    <li>📈 Empreendedorismo</li>
                    <li>📊 Análises de Negócios</li>
                    <li>📝 Criação de Planos de Negócio</li>
                    <li>🎓 Mentoria Empresarial</li>
                    <li>💡 Workshops sobre Marketing e Gestão</li>
                </ul>
            </div>
        </section>

        <section class="section">
            <h2>🗣 Testemunhos</h2>
            <div class="testimonials">
                <div class="testimonial-grid">
                    <div class="testimonial">
                        <p>"As dicas da EXCELENT BUSINESS ajudaram-me a reorganizar a minha pequena loja e duplicar as vendas."</p>
                        <div class="testimonial-author">— Carlos M., Empreendedor</div>
                    </div>
                    <div class="testimonial">
                        <p>"Os conteúdos são claros, inteligentes e aplicáveis ao dia a dia de qualquer empresa."</p>
                        <div class="testimonial-author">— Peres Mabhala, Gestor</div>
                    </div>
                </div>
            </div>
        </section>

        <section id="mvv" class="section">
            <h2>🤝 Missão, Visão e Valores</h2>
            <div class="mvv-section">
                <div class="mvv-card">
                    <h3>🌍 Missão</h3>
                    <p>Capacitar empreendedores com conhecimento prático e ferramentas inteligentes para construir negócios fortes e sustentáveis.</p>
                </div>
                <div class="mvv-card">
                    <h3>👁 Visão</h3>
                    <p>Ser referência em conteúdos de empreendedorismo em países africanos.</p>
                </div>
                <div class="mvv-card">
                    <h3>💎 Valores</h3>
                    <div class="values-list">
                        <span class="value-tag">Inovação</span>
                        <span class="value-tag">Confiança</span>
                        <span class="value-tag">Estratégia</span>
                        <span class="value-tag">Simplicidade</span>
                        <span class="value-tag">Impacto</span>
                    </div>
                </div>
            </div>
        </section>

        <section id="contacto" class="section">
            <div class="contact-section">
                <h2 style="color: #0f2027; border: none; padding: 0;">📞 Entre em Contacto</h2>
                <p style="margin-top: 1rem; font-size: 1.2rem;">Conecte-se connosco e transforme o seu negócio!</p>
                <div class="contact-links">
                    <a href="https://www.linkedin.com/in/peres-mabhala-3098b1304/" target="_blank" class="contact-btn">
                        💼 LinkedIn - Peres Mabhala
                    </a>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 EXCELENT BUSINESS. Todos os direitos reservados.</p>
        <p>Transformando ideias em negócios de sucesso através do conhecimento prático e acessível</p>
    </footer>

    <!-- Chat Assistant -->
    <button class="chat-button" id="chatButton" aria-label="Abrir assistente">
        💬
    </button>

    <div class="chat-window" id="chatWindow">
        <div class="chat-header">
            <h3>🤖 Assistente EXCELENT BUSINESS</h3>
            <button class="chat-close" id="chatClose">✕</button>
        </div>
        <div class="chat-messages" id="chatMessages">
            <div class="message bot">
                <div class="message-content">
                    Olá! 👋 Sou o assistente virtual da EXCELENT BUSINESS. Como posso ajudá-lo hoje?
                </div>
            </div>
        </div>
        <div class="chat-suggestions" id="chatSuggestions">
            <button class="suggestion-btn" data-question="Como começar um negócio?">Como começar um negócio?</button>
            <button class="suggestion-btn" data-question="Dicas de atendimento">Dicas de atendimento</button>
            <button class="suggestion-btn" data-question="Como crescer meu negócio?">Como crescer?</button>
        </div>
        <div class="chat-input-area">
            <input type="text" class="chat-input" id="chatInput" placeholder="Digite sua pergunta...">
            <button class="chat-send" id="chatSend">➤</button>
        </div>
    </div>

    <script>
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Intersection Observer for animations
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, {
            threshold: 0.1
        });

        document.querySelectorAll('.card, .section, .audience-card, .testimonial').forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(30px)';
            el.style.transition = 'all 0.6s ease';
            observer.observe(el);
        });

        // Header shadow on scroll
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if (window.scrollY > 50) {
                header.style.boxShadow = '0 4px 30px rgba(0,0,0,0.4)';
            } else {
                header.style.boxShadow = '0 4px 20px rgba(0,0,0,0.3)';
            }
        });

        // Chat Assistant
        const chatButton = document.getElementById('chatButton');
        const chatWindow = document.getElementById('chatWindow');
        const chatClose = document.getElementById('chatClose');
        const chatMessages = document.getElementById('chatMessages');
        const chatInput = document.getElementById('chatInput');
        const chatSend = document.getElementById('chatSend');
        const suggestionBtns = document.querySelectorAll('.suggestion-btn');

        // Toggle chat window
        chatButton.addEventListener('click', () => {
            chatWindow.classList.toggle('active');
        });

        chatClose.addEventListener('click', () => {
            chatWindow.classList.remove('active');
        });

        // Knowledge base expandida
        const knowledgeBase = {
            'começar': {
                keywords: ['começar', 'iniciar', 'start', 'começo', 'principiante', 'novo negócio', 'abrir empresa'],
                response: `Para começar um negócio com pouco dinheiro:

1. 🎯 Identifique uma necessidade real no mercado
2. 🏠 Comece de casa para evitar custos de aluguer
3. 📱 Use redes sociais gratuitas para divulgação
4. 💰 Ofereça serviços antes de produtos (menor investimento)
5. ♻️ Reinvista todos os lucros iniciais

Negócios para começar com menos de 5.000MT:
• Venda de bolos/doces
• Produtos de limpeza caseiros
• Recarga de telemóveis
• Cabeleireiro ao domicílio
• Explicações

Quer saber mais sobre algum destes pontos?`
            },
            'atendimento': {
                keywords: ['atendimento', 'cliente', 'clientes', 'atender', 'serviço', 'satisfação', 'experiência'],
                response: `O atendimento ao cliente é FUNDAMENTAL! 🌟

Princípios essenciais:
✓ Escute ativamente - compreenda, não apenas ouça
✓ Seja ágil - responda em menos de 2 horas
✓ Mantenha atitude positiva sempre
✓ Supere expectativas com pequenos gestos
✓ Resolva problemas no primeiro contacto

⚠️ LEMBRE-SE:
• Um cliente satisfeito conta a 3 pessoas
• Um cliente INSATISFEITO conta a 15 pessoas
• 96% dos insatisfeitos não reclamam, apenas não voltam

O atendimento pode fazer ou destruir o seu negócio!`
            },
            'crescer': {
                keywords: ['crescer', 'crescimento', 'expandir', 'desenvolver', 'aumentar', 'escalar', 'expansão'],
                response: `Estratégias para crescer o negócio: 📈

1. 👥 Construa base de clientes fiéis
   - Programa de fidelidade
   - Atendimento excepcional

2. 🎁 Marketing boca a boca
   - Incentive referências
   - Peça avaliações online

3. 📊 Controle financeiro rigoroso
   - Registe todas as transações
   - Analise o que dá mais lucro

4. 🔄 Diversifique produtos/serviços
   - Escute o que clientes precisam
   - Crie pacotes/combos

5. 🤖 Automatize processos
   - Use ferramentas gratuitas
   - Crie sistemas e rotinas

O crescimento leva tempo, mas com consistência chega!`
            },
            'marketing': {
                keywords: ['marketing', 'divulgar', 'publicidade', 'promover', 'vendas', 'propaganda', 'anúncio', 'redes sociais'],
                response: `Marketing Digital Eficaz: 📱

GRÁTIS:
• Facebook/Instagram - poste diariamente
• WhatsApp Business - contacto direto
• Google Meu Negócio - apareça nas buscas
• TikTok - vídeos curtos criativos

DICAS:
✓ Mostre bastidores do negócio
✓ Compartilhe testemunhos de clientes
✓ Faça promoções exclusivas online
✓ Responda TODOS os comentários
✓ Use fotos de qualidade

Lembre-se: Marketing não é opção, é NECESSIDADE!`
            },
            'dinheiro': {
                keywords: ['dinheiro', 'capital', 'investimento', 'financeiro', 'lucro', 'receita', 'despesa', 'finanças', 'contabilidade'],
                response: `Gestão Financeira Inteligente: 💰

REGRAS DE OURO:
1. Separe o dinheiro pessoal do empresarial
2. Registe TUDO (cada entrada e saída)
3. Reinvista nos primeiros 6 meses
4. Crie reserva de emergência (3 meses)
5. Analise lucros mensalmente

FERRAMENTAS GRATUITAS:
• Google Sheets para controlo
• Caderno de registo diário
• Apps bancários para movimentações

📊 Fórmula básica:
Lucro = Receita - Despesas
Meta: Lucro de pelo menos 30% sobre vendas`
            },
            'tempo': {
                keywords: ['tempo', 'quando', 'quanto tempo', 'demora', 'prazo', 'duração'],
                response: `Linha do Tempo Realista: ⏰

MESES 1-3: FUNDAÇÃO
• Valide a ideia
• Ajuste produto/serviço
• Construa presença online

MESES 4-6: EXPANSÃO
• Aumente produção
• Invista em marketing
• Melhore processos

MESES 7-9: PROFISSIONALIZAÇÃO
• Formalize negócio
• Considere ajuda/equipa
• Diversifique ofertas

MESES 10-12: CONSOLIDAÇÃO
• Analise resultados
• Planeie próximo ano
• Considere expansão

Sucesso não é instantâneo - é construído dia após dia!`
            },
            'plano': {
                keywords: ['plano', 'planejamento', 'planeamento', 'plano de negócio', 'business plan', 'estratégia'],
                response: `Como criar um Plano de Negócios: 📝

COMPONENTES ESSENCIAIS:
1. Sumário Executivo
   - O que é o negócio?
   - Qual problema resolve?

2. Análise de Mercado
   - Quem são seus clientes?
   - Quem são os concorrentes?

3. Produtos/Serviços
   - O que vai oferecer?
   - Qual o diferencial?

4. Plano de Marketing
   - Como vai divulgar?
   - Qual o preço?

5. Plano Financeiro
   - Quanto precisa investir?
   - Quando terá lucro?

6. Equipa
   - Quem vai trabalhar?
   - Que habilidades precisa?

Um bom plano é seu GPS para o sucesso!`
            },
            'preço': {
                keywords: ['preço', 'precificar', 'valor', 'quanto cobrar', 'custo', 'pricing'],
                response: `Como Definir Preços Corretos: 💵

FÓRMULA BÁSICA:
Preço = Custos + Despesas + Margem de Lucro

PASSOS:
1. Calcule TODOS os custos
   - Matéria-prima
   - Mão de obra
   - Embalagem

2. Some as despesas fixas
   - Aluguer, luz, água
   - Transporte
   - Marketing

3. Adicione margem de lucro
   - Mínimo: 30%
   - Ideal: 50-100%

4. Pesquise concorrentes
   - Não seja o mais barato
   - Seja o melhor custo-benefício

⚠️ NUNCA trabalhe sem lucro! Barato demais = falência rápida`
            },
            'equipa': {
                keywords: ['equipa', 'equipe', 'funcionário', 'contratar', 'colaborador', 'staff', 'recursos humanos'],
                response: `Gestão de Equipa Eficaz: 👥

QUANDO CONTRATAR?
✓ Quando o trabalho supera sua capacidade
✓ Quando pode pagar salário por 6 meses
✓ Quando há tarefas repetitivas

COMO CONTRATAR BEM:
1. Defina o perfil ideal
2. Teste habilidades práticas
3. Verifique referências
4. Comece com período de experiência

MANTER EQUIPA MOTIVADA:
• Pague em dia SEMPRE
• Dê feedback constante
• Reconheça bom trabalho
• Ofereça crescimento
• Seja líder, não chefe

Equipa feliz = clientes satisfeitos = negócio próspero!`
            },
            'online': {
                keywords: ['online', 'internet', 'digital', 'e-commerce', 'loja virtual', 'website'],
                response: `Negócio Online de Sucesso: 💻

VANTAGENS:
✓ Baixo investimento inicial
✓ Alcance global
✓ Funciona 24/7
✓ Fácil de testar ideias

PASSOS PARA COMEÇAR:
1. Escolha o produto/serviço
2. Crie presença digital
   - Instagram/Facebook (grátis)
   - WhatsApp Business
   - Site simples

3. Sistema de pagamento
   - Transferência bancária
   - M-Pesa/E-Mola
   - PayPal (internacional)

4. Logística de entrega
   - Correios
   - Motoristas parceiros
   - Entrega própria

5. Atendimento online
   - Responda rápido
   - Seja claro
   - Mostre o produto

O digital é o presente, não o futuro!`
            },
            'concorrente': {
                keywords: ['concorrente', 'concorrência', 'competidor', 'rival', 'competição'],
                response: `Como Lidar com Concorrência: 🎯

NÃO TENHA MEDO:
Concorrência prova que há mercado!

ESTRATÉGIAS:
1. Diferencie-se
   - Melhor atendimento
   - Produto único
   - Experiência superior

2. Conheça os concorrentes
   - O que fazem bem?
   - Onde falham?
   - Aprenda e adapte

3. Foque no seu cliente
   - Não compete em preço
   - Compete em valor
   - Crie relacionamento

4. Inove constantemente
   - Melhore produtos
   - Teste novidades
   - Escute feedback

5. Colabore quando possível
   - Parcerias estratégicas
   - Troca de experiências

Lembre-se: Você não precisa ser melhor que todos, precisa ser ÚNICO!`
            },
            'motivação': {
                keywords: ['motivação', 'desânimo', 'desistir', 'cansado', 'difícil', 'desmotivado'],
                response: `Mantenha-se Motivado: 💪

É NORMAL sentir-se cansado! Todo empreendedor passa por isso.

ESTRATÉGIAS:
1. Lembre porque começou
   - Escreva seus objetivos
   - Visualize o sucesso

2. Comemore pequenas vitórias
   - Primeira venda
   - Cliente satisfeito
   - Meta atingida

3. Conecte-se com outros empreendedores
   - Partilhe experiências
   - Aprenda com outros

4. Cuide de si mesmo
   - Durma bem
   - Faça pausas
   - Tenha hobbies

5. Foque no progresso, não perfeição
   - Compare-se com ontem
   - Não com outros

"O sucesso é a soma de pequenos esforços repetidos dia após dia"

Você consegue! 🌟`
            },
            'erro': {
                keywords: ['erro', 'errei', 'fracasso', 'falha', 'problema', 'deu errado'],
                response: `Lidar com Erros e Fracassos: 🔧

TODO empreendedor erra! A diferença é como reage.

QUANDO ALGO DÁ ERRADO:
1. Assuma responsabilidade
   - Não culpe outros
   - Seja honesto

2. Analise o que aconteceu
   - Por que errou?
   - O que aprendeu?

3. Corrija rapidamente
   - Cliente: resolva primeiro
   - Processo: mude depois

4. Comunique transparentemente
   - Explique o erro
   - Mostre a solução

5. Previna repetição
   - Crie sistema
   - Documente lição

LEMBRE-SE:
• Erros são lições caras, não desperdice!
• Falhar não é fracassar, desistir é!
• Grandes empresas nasceram de erros corrigidos

Continue tentando! 💪`
            },
            'fornecedor': {
                keywords: ['fornecedor', 'fornecedores', 'supplier', 'matéria-prima', 'produto', 'comprar'],
                response: `Gestão de Fornecedores: 📦

COMO ESCOLHER BEM:
1. Qualidade consistente
   - Peça amostras
   - Teste antes de comprar grande

2. Preço justo
   - Compare 3+ fornecedores
   - Negocie sempre

3. Confiabilidade
   - Entrega no prazo
   - Disponibilidade
   - Comunicação clara

4. Condições de pagamento
   - Prazo para pagar
   - Possibilidade de crédito

RELACIONAMENTO:
✓ Pague em dia
✓ Comunique-se claramente
✓ Seja profissional
✓ Construa parceria de longo prazo

DICA IMPORTANTE:
Tenha sempre 2+ fornecedores do mesmo produto.
Nunca dependa de apenas um!`
            },
            'legalização': {
                keywords: ['legalização', 'formalizar', 'registo', 'licença', 'alvará', 'documentos', 'legal'],
                response: `Formalização do Negócio: 📋

POR QUE FORMALIZAR?
✓ Acesso a financiamento
✓ Credibilidade com clientes
✓ Proteção legal
✓ Crescimento organizado

PASSOS BÁSICOS:
1. Escolha estrutura
   - Empresário individual
   - Sociedade
   - Microempresa

2. Registe a empresa
   - Conservatória/Registo Comercial
   - Número de contribuinte

3. Obtenha licenças
   - Alvará de funcionamento
   - Licenças específicas do setor

4. Abra conta bancária empresarial

5. Sistema de contabilidade

QUANDO FORMALIZAR?
Quando o faturamento justificar (geralmente após 6-12 meses).

Consulte um contador local para orientação específica!`
            },
            'produto': {
                keywords: ['produto', 'produtos', 'mercadoria', 'artigo', 'criar produto', 'desenvolver'],
                response: `Desenvolvimento de Produtos: 🎁

CRIAR PRODUTO VENCEDOR:
1. Resolva problema real
   - Ouça os clientes
   - Observe necessidades

2. Teste com mínimo viável
   - Versão básica primeiro
   - Melhore com feedback

3. Qualidade acima de tudo
   - Melhor produto médio bem feito
   - Que produto excelente mal feito

4. Embalagem importa
   - Proteja o produto
   - Impressione visualmente
   - Facilite uso

5. Diferenciais
   - O que te torna único?
   - Por que escolheriam você?

CICLO DE VIDA:
Lançamento → Crescimento → Maturidade → Renovação

Inove constantemente ou seja ultrapassado!`
            },
            'crise': {
                keywords: ['crise', 'dificuldade', 'pandemia', 'economia', 'recessão', 'vendas caindo'],
                response: `Superar Tempos Difíceis: 🛡️

EM MOMENTOS DE CRISE:

CORTE DESPESAS:
✓ Elimine o não essencial
✓ Renegocie contratos
✓ Reduza estoques

PROTEJA O CAIXA:
✓ Cobre mais rápido
✓ Pague mais devagar (com acordo)
✓ Evite novos compromissos

ADAPTE-SE:
✓ Mude produtos/serviços
✓ Explore novos canais
✓ Seja criativo

MANTENHA CLIENTES:
✓ Comunique-se mais
✓ Ofereça facilidades
✓ Mostre que está junto

OPORTUNIDADES:
• Concorrentes fracos saem
• Pode comprar barato
• Clientes valorizam lealdade

"Nunca desperdice uma boa crise" - Winston Churchill

Resiliência vence!`
            },
            'parceria': {
                keywords: ['parceria', 'parceiro', 'sociedade', 'sócio', 'colaboração'],
                response: `Parcerias Estratégicas: 🤝

QUANDO FAZER PARCERIA:
✓ Complementam habilidades
✓ Compartilham riscos/custos
✓ Expandem alcance
✓ Trazem recursos necessários

TIPOS DE PARCERIA:
1. Fornecedor preferencial
2. Canal de distribuição
3. Co-criação de produtos
4. Compartilhamento de espaço
5. Parceria de marketing

ANTES DE FIRMAR:
❗ Coloque TUDO no papel
❗ Defina responsabilidades
❗ Acordem divisão de lucros
❗ Prevejam saída/dissolução
❗ Verifiquem valores alinhados

SINAIS DE ALERTA:
🚩 Promessas vagas
🚩 Falta de transparência
🚩 Pressão para decidir rápido
🚩 Valores incompatíveis

Boa parceria multiplica resultados!
Má parceria destrói negócios!`
            },
            'tecnologia': {
                keywords: ['tecnologia', 'software', 'app', 'sistema', 'ferramenta', 'automação'],
                response: `Tecnologia para Pequenos Negócios: 💻

FERRAMENTAS GRATUITAS ESSENCIAIS:

GESTÃO:
• Trello - organização de tarefas
• Google Calendar - agendamentos
• Google Drive - arquivos

FINANCEIRO:
• Google Sheets - controlo
• Wave - contabilidade grátis
• Apps bancários

COMUNICAÇÃO:
• WhatsApp Business
• Zoom - reuniões
• Gmail - e-mail profissional

MARKETING:
• Canva - design
• Buffer - programar posts
• Google Analytics - análise

VENDAS:
• Instagram Shopping
• Facebook Marketplace
• OLX/Marketplace local

DICA:
Comece simples! Não precisa de tudo logo.
Adicione ferramentas conforme cresce.

Tecnologia é aliada, não inimiga!`
            }
        };

        function findResponse(question) {
            const lowerQuestion = question.toLowerCase();
            
            for (const [key, data] of Object.entries(knowledgeBase)) {
                if (key === 'default') continue;
                
                for (const keyword of data.keywords) {
                    if (lowerQuestion.includes(keyword)) {
                        return data.response;
                    }
                }
            }
            
            return knowledgeBase.default.response;
        }

        function addMessage(content, isUser = false) {
            const messageDiv = document.createElement('div');
            messageDiv.className = `message ${isUser ? 'user' : 'bot'}`;
            
            const contentDiv = document.createElement('div');
            contentDiv.className = 'message-content';
            contentDiv.textContent = content;
            
            messageDiv.appendChild(contentDiv);
            chatMessages.appendChild(messageDiv);
            chatMessages.scrollTop = chatMessages.scrollHeight;
        }

        function showTypingIndicator() {
            const typingDiv = document.createElement('div');
            typingDiv.className = 'message bot';
            typingDiv.id = 'typingIndicator';
            typingDiv.innerHTML = `
                <div class="typing-indicator active">
                    <span></span><span></span><span></span>
                </div>
            `;
            chatMessages.appendChild(typingDiv);
            chatMessages.scrollTop = chatMessages.scrollHeight;
        }

        function removeTypingIndicator() {
            const typingDiv = document.getElementById('typingIndicator');
            if (typingDiv) {
                typingDiv.remove();
            }
        }

        function handleQuestion(question) {
            if (!question.trim()) return;
            
            addMessage(question, true);
            chatInput.value = '';
            
            showTypingIndicator();
            
            setTimeout(() => {
                removeTypingIndicator();
                const response = findResponse(question);
                addMessage(response, false);
            }, 1000);
        }

        // Send message
        chatSend.addEventListener('click', () => {
            handleQuestion(chatInput.value);
        });

        chatInput.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                handleQuestion(chatInput.value);
            }
        });

        // Suggestion buttons
        suggestionBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                const question = btn.getAttribute('data-question');
                handleQuestion(question);
            });
        });
    </script>
</body>
</html>
