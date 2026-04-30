♻️ Agentes da Reciclagem A3P - Sefaz

O Agentes da Reciclagem é um jogo web interativo e educativo desenvolvido para promover o Dia Nacional da Reciclagem e fortalecer as ações de sustentabilidade promovidas pela Agenda Ambiental na Administração Pública (A3P) no âmbito da Secretaria de Estado de Fazenda (Sefaz).

O objetivo principal do projeto é engajar os servidores públicos de forma lúdica, ensinando e reforçando as boas práticas de descarte de resíduos (recicláveis vs. orgânicos) no ambiente corporativo.

🎯 Objetivo do Jogo

O jogador assume o controle da lixeira da coleta seletiva e tem 60 segundos para:

Coletar (Recicláveis): Papel 📄, Plástico 🧴🥤, Vidro 🍾 e Metal 🥫🔗.

Desviar (Orgânicos): Maçã 🍎, Banana 🍌, Bolo 🍰, Osso 🦴, Pizza 🍕 e Hambúrguer 🍔.

Ao capturar resíduos orgânicos por engano, o jogo é pausado e exibe uma mensagem educativa contextualizada sobre os problemas de descartar lixo orgânico nas mesas de trabalho (odores, atração de pragas, danos a equipamentos), orientando o uso exclusivo das lixeiras das Copas.

✨ Funcionalidades Principais

🕹️ Gameplay Fluido e Responsivo: Desenvolvido nativamente com HTML5 Canvas, o jogo suporta controles via teclado (setas), mouse e toque na tela (mobile).

🏆 Ranking Global (Competição Saudável): Integração com Firebase para registrar a pontuação atrelada ao e-mail institucional do servidor, criando um ranking que incentiva a participação.

📊 Contadores Individuais: Acompanhamento em tempo real da quantidade de cada tipo de material reciclável coletado durante a partida.

🤖 Inteligência Artificial (Gemini API):

Oráculo da Reciclagem: Um assistente virtual no menu principal onde os servidores podem digitar o nome de um resíduo e a IA responde imediatamente como e onde descartá-lo corretamente.

Dica Personalizada: Ao final da partida, a IA gera uma dica de sustentabilidade encorajadora com base no desempenho (pontuação) do jogador.

🎵 Áudio Procedural (Web Audio API): Trilha sonora e efeitos sonoros gerados por código matematicamente (sem arquivos MP3 pesados). Inclui som de torcida na contagem regressiva, ruídos de ambiente de escritório e músicas que mudam dinamicamente conforme o estado do jogo.

🛠️ Tecnologias Utilizadas

Este projeto foi construído em um formato "Single File" (Tudo em um único arquivo index.html), facilitando a hospedagem em qualquer servidor web simples.

Frontend: HTML5, Vanilla JavaScript (ES6 Modules) e Canvas API.

Estilização: Tailwind CSS (via CDN) com fontes do Google Fonts (Fredoka).

Backend / Banco de Dados: Firebase Authentication (Login Anônimo/Custom) e Firestore (Gravação e Leitura de Ranking).

Inteligência Artificial: Google Gemini API (modelo gemini-2.5-flash-preview-09-2025).

Áudio: Web Audio API (Sintetizadores e Filtros Biquad).

🚀 Como Executar o Projeto

Como o jogo não possui dependências complexas de build (Node.js, Webpack, etc.), a execução é extremamente simples:

Faça o download ou clone o arquivo index.html.

Abra o arquivo index.html em qualquer navegador web moderno (Google Chrome, Firefox, Edge, Safari).

Nota para Ambiente de Produção: Para que o Ranking e a Inteligência Artificial funcionem em um servidor oficial, certifique-se de configurar e injetar adequadamente as credenciais do Firebase e a Chave de API do Gemini no código (variável apiKey).

🌿 Impacto Esperado (A3P Sefaz)

Espera-se que, com a gamificação, os servidores da Sefaz:

Absorvam melhor as diretrizes de descarte correto;

Reduzam o descarte incorreto de orgânicos nas estações de trabalho;

Aumentem a triagem correta de materiais recicláveis;

Desenvolvam um senso de comunidade e responsabilidade ambiental através do ranking e do engajamento mútuo.

Desenvolvido como iniciativa de conscientização ambiental e inovação tecnológica corporativa.

Desenvolvido por Daniel Araújo - Presidente da A3P-Sefaz em 2026
