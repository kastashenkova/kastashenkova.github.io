<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kateryna Astashenkova</title>
    <style> 
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

```
    body {
        font-family: 'Georgia', 'Times New Roman', serif;
        line-height: 1.8;
        color: #2c2c2c;
        background: #f8f8f8;
        min-height: 100vh;
    }

    .container {
        max-width: 1100px;
        margin: 0 auto;
        padding: 20px;
        background: white;
        box-shadow: 0 0 20px rgba(0,0,0,0.1);
    }

    header {
        text-align: center;
        padding: 60px 20px 40px;
        border-bottom: 3px solid #2c2c2c;
        margin-bottom: 20px;
    }

    header h1 {
        font-size: 2.5em;
        margin-bottom: 10px;
        color: #1a1a1a;
        font-weight: 400;
        letter-spacing: 1px;
    }

    header p {
        font-size: 1.1em;
        color: #555;
        font-style: italic;
        margin-bottom: 20px;
    }

    .academic-note {
        max-width: 800px;
        margin: 30px auto;
        padding: 20px;
        background: #fafafa;
        border-left: 4px solid #2c2c2c;
        font-size: 0.95em;
        color: #444;
        line-height: 1.7;
    }

    .academic-note strong {
        color: #1a1a1a;
    }

    .projects {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
        gap: 30px;
        margin-top: 50px;
        padding: 0 20px;
    }

    .project-card {
        background: white;
        border: 2px solid #e0e0e0;
        transition: border-color 0.3s ease, box-shadow 0.3s ease;
    }

    .project-card:hover {
        border-color: #2c2c2c;
        box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    .project-header {
        background: #2c2c2c;
        color: white;
        padding: 25px;
        border-bottom: 3px solid #1a1a1a;
    }

    .project-header h2 {
        font-size: 1.6em;
        margin-bottom: 12px;
        font-weight: 400;
        letter-spacing: 0.5px;
    }

    .project-header .tag {
        display: inline-block;
        background: rgba(255,255,255,0.15);
        padding: 4px 12px;
        border: 1px solid rgba(255,255,255,0.3);
        font-size: 0.8em;
        margin: 5px 5px 0 0;
        font-family: 'Segoe UI', sans-serif;
    }

    .project-body {
        padding: 25px;
    }

    .project-body p {
        color: #444;
        margin-bottom: 15px;
        font-size: 0.95em;
    }

    .project-body h3 {
        color: #2c2c2c;
        margin-top: 20px;
        margin-bottom: 12px;
        font-size: 1.05em;
        font-weight: 600;
        text-transform: uppercase;
        letter-spacing: 0.5px;
        border-bottom: 1px solid #e0e0e0;
        padding-bottom: 5px;
    }

    .project-body ul {
        margin-left: 20px;
        margin-bottom: 15px;
    }

    .project-body li {
        margin: 10px 0;
        color: #555;
        font-size: 0.9em;
    }

    .tech-stack {
        display: flex;
        flex-wrap: wrap;
        gap: 8px;
        margin-top: 20px;
        padding-top: 15px;
        border-top: 1px solid #e0e0e0;
    }

    .tech-badge {
        background: white;
        padding: 6px 14px;
        font-size: 0.8em;
        color: #2c2c2c;
        border: 1px solid #d0d0d0;
        font-family: 'Courier New', monospace;
        letter-spacing: 0.5px;
    }

    .github-link {
        display: inline-block;
        margin-top: 20px;
        padding: 10px 20px;
        background: white;
        color: #2c2c2c;
        text-decoration: none;
        border: 2px solid #2c2c2c;
        transition: all 0.3s ease;
        font-weight: 600;
        font-size: 0.9em;
        letter-spacing: 0.5px;
        font-family: 'Segoe UI', sans-serif;
    }

    .github-link:hover {
        background: #2c2c2c;
        color: white;
    }

    footer {
        text-align: center;
        padding: 50px 20px 30px;
        color: #666;
        margin-top: 60px;
        border-top: 3px solid #2c2c2c;
        font-size: 0.9em;
    }

    footer a {
        color: #2c2c2c;
        text-decoration: none;
        margin: 0 15px;
        transition: color 0.3s ease;
        font-weight: 500;
    }

    footer a:hover {
        color: #666;
        text-decoration: underline;
    }

    @media (max-width: 768px) {
        header h1 {
            font-size: 2em;
        }
        
        header p {
            font-size: 1em;
        }

        .projects {
            grid-template-columns: 1fr;
        }

        .container {
            box-shadow: none;
        }
    }
</style>
```

</head>
<body>
    <div class="container">
        <header>
            <h1>Kateryna Astashenkova</h1>
            <p>Software Engineering Student at NaUKMA 2024-2028</p>
        </header>

```
    <div class="academic-note">
        Представлені нижче проєкти є навчальними роботами, створеними в межах курсів з алгоритмів і структур даних у Національному університеті «Києво-Могилянська академія». Кожен проєкт демонструє практичне застосування фундаментальних концепцій компʼютерних наук.
    </div>

    <div class="projects">
        <!-- Karel the Robot -->
        <div class="project-card">
            <div class="project-header">
                <h2>Karel the Robot</h2>
                <span class="tag">Graph Algorithms</span>
                <span class="tag">Visualization</span>
            </div>
            <div class="project-body">
                <p>Інтерактивна візуалізація алгоритмів пошуку шляху в лабіринті. Проєкт демонструє роботу BFS та DFS алгоритмів з анімованим відображенням процесу пошуку.</p>
                
                <h3>Ключові особливості</h3>
                <ul>
                    <li>Реалізація BFS та DFS алгоритмів</li>
                    <li>Покрокова анімація процесу пошуку</li>
                    <li>Підтримка різних форматів вхідних даних</li>
                    <li>Відображення метрик: довжина шляху, кількість відвіданих вершин</li>
                </ul>
                
                <div class="tech-stack">
                    <span class="tech-badge">Java</span>
                    <span class="tech-badge">Graph Theory</span>
                    <span class="tech-badge">StdDraw</span>
                    <span class="tech-badge">BFS/DFS</span>
                </div>
                
                <a href="https://github.com/kastashenkova/KarelApp" class="github-link">VIEW PROJECT →</a>
            </div>
        </div>

        <!-- Search Dictionary -->
        <div class="project-card">
            <div class="project-header">
                <h2>Search Dictionary</h2>
                <span class="tag">Data Structures</span>
                <span class="tag">Trie</span>
            </div>
            <div class="project-body">
                <p>Реалізація словника на основі префіксного дерева (Trie) з ефективним пошуком та підтримкою wildcard-запитів для роботи з текстовими даними.</p>
                
                <h3>Ключові особливості</h3>
                <ul>
                    <li>Trie структура з O(m) складністю операцій</li>
                    <li>Пошук за префіксом з використанням джокера (*)</li>
                    <li>Коректне сортування українського алфавіту</li>
                    <li>Автоматичне очищення порожніх гілок</li>
                </ul>
                
                <div class="tech-stack">
                    <span class="tech-badge">Java</span>
                    <span class="tech-badge">Trie</span>
                    <span class="tech-badge">UTF-8</span>
                    <span class="tech-badge">String Processing</span>
                </div>
                
                <a href="https://github.com/kastashenkova/Dictionary" class="github-link">VIEW PROJECT →</a>
            </div>
        </div>

        <!-- 8-Puzzle Solver -->
        <div class="project-card">
            <div class="project-header">
                <h2>8-Puzzle Solver</h2>
                <span class="tag">A* Algorithm</span>
                <span class="tag">Heuristics</span>
            </div>
            <div class="project-body">
                <p>Оптимальний розв'язувач класичної головоломки 8-Puzzle з використанням алгоритму A* та Manhattan distance евристики.</p>
                
                <h3>Ключові особливості</h3>
                <ul>
                    <li>Реалізація A* з пріоритетною чергою</li>
                    <li>Перевірка розв'язності через інверсії</li>
                    <li>Анімована візуалізація розв'язку</li>
                    <li>Hamming і Manhattan distance метрики</li>
                </ul>
                
                <div class="tech-stack">
                    <span class="tech-badge">Java</span>
                    <span class="tech-badge">A*</span>
                    <span class="tech-badge">Priority Queue</span>
                    <span class="tech-badge">Heuristics</span>
                </div>
                
                <a href="https://github.com/kastashenkova/Puzzle" class="github-link">VIEW PROJECT →</a>
            </div>
        </div>

        <!-- Embroidery Pattern -->
        <div class="project-card">
            <div class="project-header">
                <h2>Ukrainian Embroidery Designer</h2>
                <span class="tag">Graphics</span>
                <span class="tag">GUI</span>
            </div>
            <div class="project-body">
                <p>Графічний редактор для створення традиційних українських візерунків вишивки з підтримкою симетрії та дзеркального відображення.</p>
                
                <h3>Ключові особливості</h3>
                <ul>
                    <li>Чотири режими симетрії при малюванні</li>
                    <li>Вбудований візерунок "Катерина"</li>
                    <li>Функція дзеркального дублювання фрагментів</li>
                    <li>Експорт та імпорт у форматі PNG</li>
                </ul>
                
                <div class="tech-stack">
                    <span class="tech-badge">Java Swing</span>
                    <span class="tech-badge">Graphics2D</span>
                    <span class="tech-badge">BufferedImage</span>
                    <span class="tech-badge">Event Handling</span>
                </div>
                
                <a href="https://github.com/kastashenkova/Embroidery" class="github-link">VIEW PROJECT →</a>
            </div>
        </div>

        <!-- Sims NaUKMA -->
        <div class="project-card">
            <div class="project-header">
                <h2>Sims NaUKMA</h2>
                <span class="tag">Game Development</span>
                <span class="tag">Simulation</span>
            </div>
            <div class="project-body">
                <p>Симулятор студентського життя з інтерактивним кампусом НаУКМА, системою академічних тестів та управлінням персонажем.</p>
                
                <h3>Ключові особливості</h3>
                <ul>
                    <li>Інтерактивна карта кампусу з будівлями</li>
                    <li>Система генерації та проходження тестів</li>
                    <li>Управління статами персонажа</li>
                    <li>Інтеграція фонової музики та звукових ефектів</li>
                </ul>
                
                <div class="tech-stack">
                    <span class="tech-badge">Java Swing</span>
                    <span class="tech-badge">FlatLaf</span>
                    <span class="tech-badge">Game Loop</span>
                    <span class="tech-badge">Collision Detection</span>
                </div>
                
                <a href="https://github.com/kastashenkova/SimsGame" class="github-link">VIEW PROJECT →</a>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Kateryna Astashenkova | 
            <a href="https://github.com/kastashenkova" target="_blank">GitHub</a> |
            <a href="mailto:astashenkova.katya@gmail.com">Email</a>
        </p>
    </footer>
</div>
```

</body>
</html>