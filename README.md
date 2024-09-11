<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experimentos de Eletricidade Estática</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            color: #e0e0e0;
            background: linear-gradient(to bottom, #1a1a1a, #2b2b2b);
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        header, footer {
            background: #1e1e1e;
            color: #e0e0e0;
            text-align: center;
            padding: 1rem 0;
            border-top: 2px solid #b39ddb;
        }

        nav {
            background: #2b2b2b;
            padding: 1rem;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
        }

        nav a {
            color: #e0e0e0;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.2rem;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #b39ddb;
        }

        .container {
            padding: 5rem 1rem 2rem;
            max-width: 900px;
            margin: 0 auto;
        }

        h1, h2, h3 {
            color: #b39ddb;
        }

        main {
            background: #2b2b2b;
            padding: 2rem;
            margin-top: 60px; /* Space for fixed nav */
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }

        p, ul, ol {
            margin-bottom: 1rem;
        }

        ul, ol {
            padding-left: 1.5rem;
        }

        .button {
            display: block;
            text-align: center;
            font-size: 1.2rem;
            color: #b39ddb;
            text-decoration: none;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            background: #1e1e1e;
            transition: background 0.3s ease, color 0.3s ease;
            margin-top: 2rem;
        }

        .button:hover {
            background: #b39ddb;
            color: #fff;
        }

        .welcome-page, .menu-page {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background: #1a1a1a;
            text-align: center;
            padding: 2rem;
        }

        .welcome-page h1, .menu-page h1 {
            color: #b39ddb;
            margin-bottom: 1rem;
        }

        .menu-page a {
            display: block;
            margin: 10px 0;
            font-size: 1.5rem;
            color: #e0e0e0;
            text-decoration: none;
            background: #b39ddb;
            padding: 1rem 2rem;
            border-radius: 5px;
            transition: background 0.3s ease, transform 0.3s ease;
        }

        .menu-page a:hover {
            background: #9e8bde;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="#welcome">Início</a>
            <a href="#eletrizacao">Eletrização por Contato</a>
            <a href="#maquina-choque">Máquina de Choque</a>
            <a href="#outros-experimentos">Outros Experimentos</a>
        </nav>
    </header>

    <div id="welcome" class="welcome-page">
        <h1>Experimentos de Eletricidade Estática</h1>
        <p>Explore conceitos fascinantes de eletricidade estática com nossos experimentos. Clique abaixo para começar com o experimento principal ou veja outros experimentos interessantes.</p>
        <a href="#menu" class="button">Começar</a>
    </div>

    <div id="menu" class="menu-page">
        <h1>Menu</h1>
        <p>Escolha uma das seções abaixo para saber mais:</p>
        <a href="#eletrizacao">Experimento de Eletrização por Contato</a>
        <a href="#maquina-choque">Máquina de Choque Caseira</a>
        <a href="#outros-experimentos">Outros Experimentos</a>
    </div>

    <main id="eletrizacao">
        <h2>Experimento de Eletrização por Contato</h2>
        <p>O experimento de eletrização por contato é uma maneira fascinante e simples de demonstrar como objetos podem adquirir cargas elétricas e interagir com outros objetos. Este experimento é ótimo para entender o conceito básico de eletricidade estática.</p>

        <h3>Material Necessário</h3>
        <ul>
            <li><strong>Balões:</strong> Balões de látex são ideais para este experimento. Eles são flexíveis e podem facilmente acumular carga estática.</li>
            <li><strong>Pedaços de Papel:</strong> Use pequenos pedaços de papel, como papel toalha ou papel de seda, que são leves e facilmente atraídos pela eletricidade estática.</li>
            <li><strong>Tecido:</strong> Tecido de lã ou algodão funciona bem para esfregar o balão e gerar eletricidade estática. Tente diferentes tipos para ver qual gera mais carga.</li>
        </ul>

        <h3>Instruções Detalhadas</h3>
        <ol>
            <li><strong>Inflação:</strong> Infle um balão até que esteja bem esticado e dê um nó para evitar que o ar escape.</li>
            <li><strong>Esfregar:</strong> Pegue um pedaço de tecido e esfregue-o vigorosamente contra o balão. A fricção transfere elétrons para o balão, carregando-o negativamente.</li>
            <li><strong>Testar:</strong> Segure o balão próximo aos pedaços de papel e observe como eles são atraídos para o balão. Isso acontece porque o balão carregado negativamente cria uma força eletrostática que atrai o papel.</li>
            <li><strong>Experimentos Adicionais:</strong> Experimente esfregar o balão em diferentes tipos de tecido (lã, algodão, sintético) e veja qual tipo gera mais eletricidade estática. Tente também usar diferentes materiais, como pequenas bolas de isopor, para ver como eles reagem ao balão.</li>
        </ol>

        <h3>Explicação Científica</h3>
        <p>Quando você esfrega o balão contra o tecido, ocorre uma transferência de elétrons. O balão ganha elétrons e fica carregado negativamente, enquanto o tecido perde elétrons e fica carregado positivamente. A interação entre essas cargas opostas cria uma força que atrai objetos leves, como os pedaços de papel, para o balão.</p>
        <p>Este experimento ilustra a lei fundamental da eletrostática: cargas opostas se atraem e cargas semelhantes se repelem. É uma forma prática de observar a força eletrostática e a transferência de carga elétrica.</p>

        <h3>Aplicações Práticas e Variações</h3>
        <p>Além de ser um experimento educativo, a eletrização por contato tem várias aplicações práticas. A eletricidade estática é utilizada em impressoras a laser e em processos industriais para controlar poeira e particulados. Você também pode usar este experimento para criar pequenas experiências artísticas, como fazer pequenas "esculturas" com papel atraído pelo balão.</p>
        <p>Experimentos semelhantes incluem a utilização de um gerador de Van de Graaff para criar cargas muito maiores e mais visíveis, ou a utilização de esferas metálicas para demonstrar a distribuição da carga elétrica.</p>

        <a href="#menu" class="button">Voltar ao Menu</a>
    </main>

    <main id="maquina-choque">
        <h2>Máquina de Choque Caseira</h2>
        <p>A máquina de choque caseira é um projeto interessante que utiliza eletricidade estática para gerar um choque elétrico. É uma excelente maneira de demonstrar o acúmulo e a liberação de eletricidade estática.</p>
        <h3>Como Funciona</h3>
        <p>A máquina de choque caseira utiliza um gerador de Van de Graaff para acumular eletricidade estática. O gerador cria uma grande diferença de potencial elétrico, que é armazenada em um capacitor. Quando a carga atinge um nível alto, ela é descarregada ao tocar um objeto condutor, como uma esfera metálica, gerando um choque elétrico.</p>

        <a href="#menu" class="button">Voltar ao Menu</a>
    </main>

    <main id="outros-experimentos">
        <h2>Outros Experimentos de Eletricidade Estática</h2>
        <p>Aqui estão alguns outros experimentos interessantes que você pode tentar em casa para entender mais sobre eletricidade estática.</p>
        <ul>
            <li><strong>Gerador de Van de Graaff Caseiro:</strong> Um gerador de Van de Graaff é uma máquina que acumula eletricidade estática em uma esfera metálica. Você pode construir um com materiais simples.</li>
            <li><strong>Experimentos com Condutores e Isolantes:</strong> Teste a diferença entre condutores e isolantes usando objetos do cotidiano e veja quais permitem que a eletricidade estática flua mais facilmente.</li>
            <li><strong>Atração de Objetos com Eletricidade Estática:</strong> Experimente usar diferentes materiais para gerar eletricidade estática e observe como diferentes objetos reagem à carga.</li>
        </ul>

        <a href="#menu" class="button">Voltar ao Menu</a>
    </main>

    <footer>
        <p>&copy; 2023 - Experimentos de Eletricidade Estática</p>
    </footer>
</body>
</html>
