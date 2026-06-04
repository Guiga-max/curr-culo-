<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo - Guilherme Guimarães Azevedo</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
            padding: 40px 20px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #ffffff;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        header {
            text-align: center;
            border-bottom: 2px solid #3498db;
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        header h1 {
            color: #2c3e50;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        .contato {
            font-size: 0.9rem;
            color: #7f8c8d;
        }

        .contato span {
            margin: 0 10px;
        }

        section {
            margin-bottom: 30px;
        }

        section h2 {
            color: #2c3e50;
            font-size: 1.4rem;
            margin-bottom: 15px;
            position: relative;
            padding-bottom: 5px;
        }

        section h2::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 50px;
            height: 3px;
            background-color: #3498db;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }

        .skill-item {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 6px;
            border-left: 4px solid #3498db;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .skill-name {
            font-weight: 600;
            color: #34495e;
        }

        .skill-level {
            font-size: 0.85rem;
            background: #e1f5fe;
            color: #0288d1;
            padding: 4px 10px;
            border-radius: 20px;
            font-weight: bold;
        }

        .instituicao {
            display: block;
            font-size: 0.8rem;
            color: #7f8c8d;
            margin-top: 2px;
        }

        .objetivo p {
            color: #555;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Guilherme Guimarães Azevedo</h1>
            <div class="contato">
                <span>📍 Recife-PE></span> | 
                <span>📞 (81) 99152-1372</span> | 
                <span>✉️ guigaazevedo@gmail.com</span>
            </div>
            <div class="contato" style="margin-top: 5px;">
                <span>🔗 https://www.linkedin.com/in/guilherme-guimar%C3%A3es-a54256354</span> | 
                <span>💻 https://github.com/Guiga-max</span>
            </div>
        </header>

        <section class="objetivo">
            <h2>Objetivo</h2>
            <p>Busco oportunidade para ingressar na área de tecnologia, aplicando meus conhecimentos em lógica de programação e desenvolvimento de software, visando contribuir para os resultados da empresa e evoluir profissionalmente.</p>
        </section>

        <section>
            <h2>Skills / Competências</h2>
            <div class="skills-grid">
                
                <div class="skill-item">
                    <div>
                        <span class="skill-name">Python</span>
                    </div>
                    <span class="skill-level">Intermediário</span>
                </div>

                <div class="skill-item">
                    <div>
                        <span class="skill-name">Microsoft Excel 2016</span>
                        <span class="instituicao">Fundação Bradesco</span>
                    </div>
                    <span class="skill-level">Intermediário</span>
                </div>

                <div class="skill-item">
                    <div>
                        <span class="skill-name">JavaScript</span>
                    </div>
                    <span class="skill-level">Básico</span>
                </div>

                <div class="skill-item">
                    <div>
                        <span class="skill-name">HTML5 & CSS3</span>
                    </div>
                    <span class="skill-level">Básico</span>
                </div>

                <div class="skill-item">
                    <div>
                        <span class="skill-name">Lógica de Programação</span>
                    </div>
                    <span class="skill-level">avançado</span>
                </div>

            </div>
        </section>

        <section>
            <h2>Formação Acadêmica</h2>
            <p><strong>Ensino Medio</strong></p>
            <p style="color: #7f8c8d; font-size: 0.9rem;">Adventista | inicio: 2025 termino:2027</p>
        </section>
    </div>

</body>
</html>
