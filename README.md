# Plataforma-Dislexixa-e-Apoio

Plataforma web inclusiva e gamificada de apoio psicopedagógico para estudantes com dislexia (12-18 anos), educadores e responsáveis.

Sistema Web Inclusivo para Apoio Psicopedagógico — uma plataforma gratuita, acessível (WCAG 2.1 AA) e gamificada para apoiar estudantes com dislexia (12–18 anos), educadores e responsáveis.

Projeto Integrador III 
Curso Técnico em Informática para Internet 
IFTO (Instituto Federal de Educação, Ciência e Tecnologia do Tocantins) 
Campus Palmas Autor: Gabriel Andrade Rodriguez

🎯 Sobre o projeto

A dislexia afeta entre 5% e 17% da população brasileira (cerca de 7,8 milhões de pessoas). Apenas 25,2% dos alunos com deficiência concluem o ensino médio (contra 53,4% dos alunos sem deficiência), e 82,2% dos disléxicos relatam baixa autoestima. Ferramentas especializadas tradicionais custam entre R$ 5.000 e R$ 15.000 por mês — inacessíveis para a maioria das famílias.

A DISLEXIA e APOIO nasce para democratizar esse suporte: uma plataforma web open-source, gamificada e alinhada à LBI (2015), à LGPD e ao ODS 4 da ONU.

✨ Funcionalidades

Três perfis de usuário: Aluno, Educador e Responsável (+ Administrador)
5 jogos educativos cobrindo diferentes habilidades de leitura/escrita:

Jogo	Habilidade treinada

🧩 Memória de Palavras	Associação imagem–palavra

🔤 Quiz Fonológico	Rimas e consciência silábica

🗂️ Categorização de Palavras	Classificação semântica

🔢 Sequência Lógica	Ordenação de eventos / raciocínio sequencial

🎧 Leitura Assistida	Leitura com narração (TTS) + compreensão textual

Dashboard do Aluno: progresso, pontos, badges e recomendações

Painel do Educador: acertos/erros por aluno e por tipo de atividade, com sugestões automáticas de reforço pedagógico

Painel dos Responsáveis: resumo simples do progresso + dicas de apoio em casa

Acessibilidade (WCAG 2.1 AA): fonte ajustável (12–24px), alto contraste, narração por voz (Web Speech API), navegação por teclado

Comunidade moderada e página de contato/suporte

🛠️ Tecnologias

Frontend: HTML5, CSS3, JavaScript (ES6+) — SPA sem recarregamento de página

Acessibilidade: Web Speech API (Text-to-Speech e destaque de palavras)

Persistência: armazenamento local de progresso do aluno

Backend sugerido (evolução futura): Node.js/Express ou PHP + MySQL

🚀 Como executar

Este é um protótipo front-end funcional em um único arquivo HTML — não requer instalação nem servidor.

bash

# Clone o repositório
git clone https://github.com/gabrielrodriguez-data/Plataforma-Dislexixa-e-Apoio.git

# Entre na pasta
cd Plataforma-Dislexixa-e-Apoio

🚀 Demonstração e Acesso Online

Você pode acessar e testar o jogo diretamente pelo navegador através do GitHub Pages , sem a necessidade de instalação prévia:

👉 Acessar o Jogo Online (https://gabrielrodriguez-data.github.io/Plataforma-Dislexixa-e-Apoio/)

# Abra o arquivo direto no navegador

# (duplo clique em index.html ou use uma extensão "Live Server")

📂 Estrutura do repositório

dislexia-e-apoio/
├── index.html          # Plataforma completa (landing, login, dashboards, jogos)
└── README.md

♿ Acessibilidade

Todos os controles de acessibilidade ficam fixos no topo da tela, em qualquer página:

🔠 Tamanho da letra (12px–24px)
🐢 Velocidade da narração (0.5x–2x)
🌗 Alto contraste
🔊 Narração por voz
📖 Fundamentação

O design dos jogos foi orientado por pesquisas sobre intervenções lúdicas em dislexia, com foco em:

Consciência fonológica (rimas, sílabas)
Ambiente sem julgamento, que reduz a ansiedade do erro
Feedback imediato e gamificação para sustentar motivação
Acompanhamento de educadores e responsáveis como parte do processo

Jogos são um recurso de apoio à aprendizagem — não substituem diagnóstico ou acompanhamento profissional especializado.

📜 Licença e uso

Projeto acadêmico desenvolvido para fins educacionais no âmbito do Projeto Integrador III (IFTO). Livre para uso e adaptação em contextos educacionais não comerciais.

👤 Autor

Gabriel Andrade Rodriguez 
Curso Técnico em Informática para Internet 
IFTO, Campus Palmas 
Orientação: Prof. Me. Francirley Resendes Borges Costa
