<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Santiago Horta Hurtado</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #333; max-width: 850px; margin: 0 auto; padding: 20px; background: #e9ecef; }
        .cv-container { background: white; padding: 40px; border-radius: 10px; box-shadow: 0 5px 20px rgba(0,0,0,0.08); }
        .header-container { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; }
        h1 { margin: 0; color: #1a5276; font-size: 2.6em; letter-spacing: -0.5px; line-height: 1.1; }
        .subtitle { color: #555; font-size: 1.3em; font-weight: 600; margin-top: 5px; }
        .logo-img { 
            max-width: 100px; 
            background-color: #1a5276; 
            padding: 10px; 
            border-radius: 10px; 
            box-shadow: 0 4px 8px rgba(0,0,0,0.2); 
        }
        .contact-info { display: flex; flex-wrap: wrap; gap: 15px; margin-bottom: 25px; font-size: 0.95em; color: #444; border-bottom: 1px solid #eee; padding-bottom: 20px; }
        .contact-info a { color: #2980b9; text-decoration: none; font-weight: bold; transition: color 0.3s; }
        .contact-info a:hover { color: #1a5276; text-decoration: underline; }
        .profile { background: #f8f9fa; padding: 15px 20px; border-left: 4px solid #2980b9; margin-bottom: 30px; font-size: 0.95em; color: #444; border-radius: 0 5px 5px 0; }
        h2 { border-bottom: 2px solid #2980b9; padding-bottom: 8px; color: #1a5276; margin-top: 30px; font-size: 1.5em; text-transform: uppercase; letter-spacing: 1px; }
        .job { margin-bottom: 25px; }
        .job h3 { margin: 5px 0; color: #2c3e50; font-size: 1.2em; }
        .date { font-style: italic; color: #7f8c8d; font-size: 0.9em; margin-bottom: 10px; }
        .skills-container { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 15px; margin-bottom: 10px; }
        .skill-tag { background: #ebf5fb; color: #1a5276; padding: 6px 14px; border-radius: 20px; font-size: 0.85em; font-weight: bold; border: 1px solid #d4e6f1; box-shadow: 0 1px 3px rgba(0,0,0,0.05); }
        .skill-tag.ops { background: #fdf2e9; color: #d35400; border-color: #fae5d3; }
        ul { padding-left: 20px; margin-top: 10px; }
        li { margin-bottom: 8px; font-size: 0.95em; }
        .edu-details { font-size: 0.9em; color: #666; display: block; margin-top: 2px; }
        @media (max-width: 600px) { .header-container { flex-direction: column-reverse; align-items: flex-start; gap: 15px; } }
    </style>
</head>
<body>
    <div class="cv-container">
        <div class="header-container">
            <div>
                <h1>Santiago Horta Hurtado</h1>
                <div class="subtitle">Data Engineer & AI Systems Architect</div>
            </div>
            <img src="surdao.svg" alt="SUR DAO Logo" class="logo-img">
        </div>

        <div class="contact-info">
            <span>📍 Buenos Aires, Argentina</span>
            <span>📱 +54 9 236 4554101</span>
            <span>📧 santiago.horta@gmail.com</span>
            <span>🔗 <a href="https://github.com/TIANHH77/surdao" target="_blank">GitHub: TIANHH77/surdao</a></span>
        </div>

        <div class="profile">
            <strong>Resumen Profesional:</strong> Arquitecto de datos y sistemas de IA con una visión integral orientada al negocio. Combino una fuerte base técnica en Ingeniería de Datos, MLOps y Arquitecturas RAG con una sólida trayectoria en gestión operativa y atención al cliente. Experto en convertir grandes volúmenes de datos en soluciones técnicas eficientes, manteniendo siempre un enfoque centrado en la excelencia del servicio, la resolución de conflictos y la optimización de procesos operativos.
        </div>

        <h2>Habilidades Técnicas y Operativas</h2>
        <div class="skills-container">
            <span class="skill-tag">Python (Avanzado)</span>
            <span class="skill-tag">SQL & DuckDB (Avanzado)</span>
            <span class="skill-tag">Arquitecturas RAG & LLMs</span>
            <span class="skill-tag">Data Pipelines / ETL</span>
            <span class="skill-tag">Pandas & FastAPI</span>
            <span class="skill-tag ops">Atención al Cliente (KPIs)</span>
            <span class="skill-tag ops">Logística e Inventario</span>
            <span class="skill-tag ops">Auditoría de Procesos (ISO)</span>
            <span class="skill-tag ops">Resolución de Conflictos</span>
        </div>

        <h2>Experiencia Profesional Destacada</h2>
        <div class="job">
            <h3>Data Engineer & MLOps Architect | Proyecto SUR DAO</h3>
            <div class="date">Ene 2024 – Presente</div>
            <ul>
                <li><strong>Arquitectura de Data Lake:</strong> Diseño y procesamiento de +510 millones de registros gubernamentales para auditoría socioeconómica.</li>
                <li><strong>Optimización MLOps:</strong> Desarrollo de pipelines de ingesta automatizada y queries de alto rendimiento con DuckDB in-memory, eliminando cuellos de botella en series de datos de 17+ años.</li>
            </ul>
        </div>

        <div class="job">
            <h3>Operario de Logística | Pharmacorp</h3>
            <div class="date">2024 – 2025</div>
            <ul>
                <li>Gestión técnica de inventario bajo normativas estrictas de calidad, asegurando la trazabilidad y eficiencia en la cadena de suministro.</li>
            </ul>
        </div>
        
        <div class="job">
            <h3>Analista de Capacitación | OTEC I-CAP</h3>
            <ul>
                <li>Diseño y relatoría de 32 cursos técnicos (SENCE) para 500 ejecutivos, gestionando la comunicación efectiva y el seguimiento de competencias técnicas.</li>
            </ul>
        </div>

        <div class="job">
            <h3>Ejecutivo de Atención al Cliente | Gasco, VTR, Claro, Cadem</h3>
            <ul>
                <li>Gestión integral de clientes y resolución de conflictos bajo KPIs de alta exigencia. Resolución técnica de beneficios sociales y encuestas, manteniendo estándares de calidad en entornos de alto flujo.</li>
            </ul>
        </div>

        <h2>Educación y Certificaciones</h2>
        <ul>
            <li><strong>Computer Science (CS50)</strong> | Universidad de Harvard (En curso).</li>
            <li><strong>Tech AI Builder (ONE AI for Tech)</strong> | Oracle (En curso). 
                <span class="edu-details">Formaciones en: IA Generativa, Ingeniería de Agentes, Inteligencia de Datos & RAG Avanzado, y Oracle Cloud Infrastructure.</span>
            </li>
            <li><strong>Bachiller en Terapia Ocupacional Crítica</strong> | USACH (2021-2023).</li>
            <li><strong>Auditor Interno ISO 9001</strong> e <strong>Interpretación Norma Chilena 2728:2015</strong> | SGS.</li>
            <li><strong>Inglés:</strong> Nivel B1 (Técnico y Lectura).</li>
        </ul>
    </div>
</body>
</html>
