<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sintonizados — Louvor & Palavra</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Playfair+Display:ital,wght@0,600;0,800;1,400&display=swap');
        
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
        }
        
        .font-serif-title {
            font-family: 'Playfair Display', serif;
        }

        .glass-card {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(229, 231, 235, 0.8);
        }

        .gradient-text {
            background: linear-gradient(135deg, #4F46E5 0%, #7C3AED 50%, #DB2777 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .gradient-bg {
            background: linear-gradient(135deg, #4F46E5 0%, #7C3AED 50%, #C026D3 100%);
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #F3F4F6;
        }
        ::-webkit-scrollbar-thumb {
            background: #C7D2FE;
            border-radius: 3px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #818CF8;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 min-h-screen flex flex-col selection:bg-indigo-500 selection:text-white">

    <!-- Header / Navbar -->
    <header class="sticky top-0 z-40 bg-white/80 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-6xl mx-auto px-4 py-3 flex items-center justify-between">
            <div class="flex items-center gap-3 cursor-pointer" onclick="switchTab('explore')">
                <div class="p-2.5 gradient-bg rounded-2xl text-white shadow-md shadow-indigo-200">
                    <i data-lucide="radio" class="w-6 h-6"></i>
                </div>
                <div>
                    <h1 class="text-xl font-bold font-serif-title tracking-tight text-slate-900 leading-none">Sintonizados</h1>
                    <p class="text-xs font-medium text-indigo-600 mt-0.5">Louvor & Palavra</p>
                </div>
            </div>

            <!-- Navegação Desktop -->
            <nav class="hidden md:flex items-center gap-1 bg-slate-100 p-1 rounded-xl text-sm font-medium">
                <button onclick="switchTab('explore')" id="nav-explore" class="px-4 py-2 rounded-lg transition-all text-slate-600 hover:text-slate-900">
                    <i data-lucide="compass" class="w-4 h-4 inline mr-1.5"></i>Explorar por Tema
                </button>
                <button onclick="switchTab('ai-search')" id="nav-ai-search" class="px-4 py-2 rounded-lg transition-all text-slate-600 hover:text-slate-900">
                    <i data-lucide="sparkles" class="w-4 h-4 inline mr-1.5 text-amber-500"></i>Sintonizador IA
                </button>
                <button onclick="switchTab('playlist')" id="nav-playlist" class="px-4 py-2 rounded-lg transition-all text-slate-600 hover:text-slate-900 relative">
                    <i data-lucide="list-music" class="w-4 h-4 inline mr-1.5"></i>Minha Seleção
                    <span id="playlist-count" class="hidden absolute -top-1 -right-1 bg-indigo-600 text-white text-[10px] w-5 h-5 rounded-full flex items-center justify-center font-bold">0</span>
                </button>
            </nav>

            <button onclick="openAboutModal()" class="text-slate-500 hover:text-indigo-600 p-2 rounded-lg hover:bg-slate-100 transition">
                <i data-lucide="info" class="w-5 h-5"></i>
            </button>
        </div>
    </header>

    <!-- Conteúdo Principal -->
    <main class="flex-grow max-w-6xl w-full mx-auto px-4 py-6 md:py-8">

        <!-- ABA 1: EXPLORAR POR TEMA -->
        <section id="tab-explore" class="space-y-8">
            <!-- Hero Banner -->
            <div class="relative rounded-3xl overflow-hidden gradient-bg text-white p-6 md:p-10 shadow-xl shadow-indigo-100">
                <div class="absolute -right-10 -bottom-10 w-64 h-64 bg-white/10 rounded-full blur-2xl pointer-events-none"></div>
                <div class="max-w-2xl relative z-10 space-y-3">
                    <span class="inline-flex items-center gap-1.5 text-xs font-semibold uppercase tracking-wider bg-white/20 px-3 py-1 rounded-full text-indigo-100 backdrop-blur-sm">
                        <i data-lucide="book-open" class="w-3.5 h-3.5"></i> Harmonia Espiritual
                    </span>
                    <h2 class="text-2xl md:text-4xl font-extrabold font-serif-title leading-tight">Encontre a trilha sonora ideal para a sua pregação ou oração.</h2>
                    <p class="text-indigo-100 text-sm md:text-base leading-relaxed">Conecte o tema da Palavra de hoje com hinos e louvores que enriquecem o momento de adoração na sua célula, culto ou devocional diário.</p>
                </div>
            </div>

            <!-- Seleção de Categorias/Temas -->
            <div>
                <div class="flex items-center justify-between mb-4">
                    <h3 class="text-lg font-bold text-slate-800 flex items-center gap-2">
                        <i data-lucide="tag" class="w-5 h-5 text-indigo-600"></i> Escolha o Tema da Palavra
                    </h3>
                    <span class="text-xs text-slate-500">Selecione uma palavra-chave</span>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-3" id="topics-grid">
                    <!-- Categorias inseridas via JS -->
                </div>
            </div>

            <!-- Lista de Recomendações -->
            <div id="songs-container" class="space-y-4">
                <div class="flex items-center justify-between border-b border-slate-200 pb-3">
                    <div>
                        <h3 class="text-xl font-bold text-slate-900" id="current-topic-title">Todas as Palavras</h3>
                        <p class="text-xs text-slate-500" id="current-topic-desc">Louvores selecionados para edificação espiritual</p>
                    </div>
                    <span id="songs-count" class="text-xs font-semibold bg-indigo-50 text-indigo-700 px-3 py-1 rounded-full border border-indigo-100">0 louvores</span>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-4" id="songs-list">
                    <!-- Cards de Louvores inseridos via JS -->
                </div>
            </div>
        </section>

        <!-- ABA 2: SINTONIZADOR COM IA (GEMINI) -->
        <section id="tab-ai-search" class="hidden space-y-6">
            <div class="bg-gradient-to-br from-indigo-900 via-purple-900 to-slate-900 text-white p-6 md:p-8 rounded-3xl shadow-xl relative overflow-hidden">
                <div class="max-w-2xl space-y-3 relative z-10">
                    <div class="inline-flex items-center gap-1.5 bg-amber-500/20 text-amber-300 border border-amber-500/30 text-xs px-3 py-1 rounded-full font-medium">
                        <i data-lucide="sparkles" class="w-3.5 h-3.5"></i> Recomendações com Inteligência Artificial
                    </div>
                    <h2 class="text-2xl md:text-3xl font-bold font-serif-title">Digite um versículo, tema de pregação ou como você se sente</h2>
                    <p class="text-slate-300 text-sm">Nossa inteligência artificial analisa a Palavra ou o momento e sintoniza louvores perfeitos para ministrar ao coração.</p>
                </div>
            </div>

            <!-- Formulário de IA -->
            <div class="glass-card p-5 rounded-2xl shadow-sm space-y-4">
                <div>
                    <label class="block text-sm font-semibold text-slate-700 mb-1">Qual é a Palavra, Trecho do Esboço ou Sentimento?</label>
                    <textarea id="ai-input" rows="3" class="w-full p-3.5 rounded-xl border border-slate-200 focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 text-sm resize-none" placeholder="Ex: 'Estou preparando uma palavra sobre Salmo 23, confiança no vale da sombra da morte' ou 'Tema: Perdão e restauração da família'"></textarea>
                </div>

                <div class="flex flex-wrap items-center justify-between gap-3">
                    <div class="flex flex-wrap gap-2 text-xs">
                        <span class="text-slate-400 self-center">Exemplos:</span>
                        <button onclick="setAiExample('Salmos 46:1 - Deus é o nosso refúgio e fortaleza')" class="bg-slate-100 hover:bg-indigo-50 text-slate-600 hover:text-indigo-600 px-2.5 py-1 rounded-lg transition">Salmos 46:1</button>
                        <button onclick="setAiExample('Superação de ansiedade e descanso na promessa')" class="bg-slate-100 hover:bg-indigo-50 text-slate-600 hover:text-indigo-600 px-2.5 py-1 rounded-lg transition">Vencendo a Ansiedade</button>
                        <button onclick="setAiExample('Gratidão pelas bênçãos do ano')" class="bg-slate-100 hover:bg-indigo-50 text-slate-600 hover:text-indigo-600 px-2.5 py-1 rounded-lg transition">Gratidão</button>
                    </div>

                    <button onclick="generateAiRecommendations()" id="btn-ai-submit" class="gradient-bg text-white font-semibold px-6 py-2.5 rounded-xl shadow-md shadow-indigo-200 hover:opacity-95 transition flex items-center gap-2 text-sm w-full sm:w-auto justify-center">
                        <i data-lucide="wand-2" class="w-4 h-4"></i> Sintonizar Louvores
                    </button>
                </div>
            </div>

            <!-- Loader -->
            <div id="ai-loading" class="hidden py-12 text-center space-y-3">
                <div class="inline-block animate-spin rounded-full h-8 w-8 border-4 border-indigo-600 border-t-transparent"></div>
                <p class="text-slate-600 text-sm font-medium">Buscando na palavra e sintonizando os melhores louvores...</p>
            </div>

            <!-- Resultados da IA -->
            <div id="ai-results" class="space-y-4"></div>
        </section>

        <!-- ABA 3: MINHA SELEÇÃO / PLAYLIST -->
        <section id="tab-playlist" class="hidden space-y-6">
            <div class="flex items-center justify-between border-b border-slate-200 pb-4">
                <div>
                    <h2 class="text-2xl font-bold text-slate-900 font-serif-title">Sua Playlist da Mensagem</h2>
                    <p class="text-xs text-slate-500">Louvores guardados para o seu culto, célula ou momento individual</p>
                </div>
                <button onclick="clearPlaylist()" id="btn-clear-playlist" class="text-xs text-rose-600 hover:text-rose-700 bg-rose-50 hover:bg-rose-100 px-3 py-1.5 rounded-lg transition font-medium hidden">
                    Limpar Lista
                </button>
            </div>

            <div id="playlist-empty" class="text-center py-16 space-y-3 bg-white rounded-2xl border border-dashed border-slate-300 p-6">
                <div class="w-12 h-12 bg-indigo-50 text-indigo-500 rounded-full flex items-center justify-center mx-auto">
                    <i data-lucide="music-2" class="w-6 h-6"></i>
                </div>
                <h3 class="text-base font-semibold text-slate-800">Sua seleção está vazia</h3>
                <p class="text-xs text-slate-500 max-w-sm mx-auto">Navegue pelas palavras ou use a busca por IA para adicionar hinos à sua lista do culto ou estudo.</p>
                <button onclick="switchTab('explore')" class="mt-2 text-xs gradient-bg text-white font-semibold px-4 py-2 rounded-xl">
                    Explorar Louvores
                </button>
            </div>

            <div id="playlist-items" class="grid grid-cols-1 md:grid-cols-2 gap-4"></div>
        </section>

    </main>

    <!-- Modal Detalhes do Louvor -->
    <div id="song-modal" class="fixed inset-0 bg-slate-900/60 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-white w-full max-w-2xl rounded-3xl shadow-2xl overflow-hidden flex flex-col max-h-[90vh]">
            <!-- Header Modal -->
            <div class="gradient-bg text-white p-6 relative">
                <button onclick="closeSongModal()" class="absolute top-4 right-4 text-white/80 hover:text-white p-1 rounded-full bg-black/10 hover:bg-black/20 transition">
                    <i data-lucide="x" class="w-5 h-5"></i>
                </button>
                <span id="modal-tag" class="text-[10px] font-bold uppercase tracking-wider bg-white/20 px-2.5 py-0.5 rounded-full text-indigo-100 inline-block mb-2">Tema</span>
                <h3 id="modal-title" class="text-2xl font-bold font-serif-title leading-tight">Nome da Música</h3>
                <p id="modal-artist" class="text-indigo-100 text-sm mt-0.5">Artista / Ministérios</p>
            </div>

            <!-- Body Modal -->
            <div class="p-6 overflow-y-auto space-y-5 flex-grow">
                <!-- Conexão com a Palavra -->
                <div class="bg-indigo-50/60 border border-indigo-100 p-4 rounded-2xl space-y-1">
                    <h4 class="text-xs font-bold text-indigo-900 uppercase tracking-wide flex items-center gap-1.5">
                        <i data-lucide="book-open" class="w-4 h-4 text-indigo-600"></i> Conexão Teológica & Versículo
                    </h4>
                    <p id="modal-bible-ref" class="text-sm font-semibold text-slate-800">Versículo Chave</p>
                    <p id="modal-explanation" class="text-xs text-slate-600 leading-relaxed pt-1">Explicação da relação entre a palavra e o louvor.</p>
                </div>

                <!-- Trecho em Destaque -->
                <div>
                    <h4 class="text-xs font-bold text-slate-400 uppercase tracking-wider mb-2">Trecho Marcante da Letra</h4>
                    <div class="bg-slate-50 p-4 rounded-2xl border border-slate-200 italic text-slate-700 text-sm leading-relaxed border-l-4 border-l-indigo-600 font-serif-title" id="modal-lyric">
                        "Trecho da letra..."
                    </div>
                </div>

                <!-- Link Busca / Player -->
                <div class="pt-2 flex flex-col sm:flex-row gap-2">
                    <a id="modal-youtube" href="#" target="_blank" class="flex-1 bg-red-600 hover:bg-red-700 text-white text-xs font-semibold py-2.5 px-4 rounded-xl flex items-center justify-center gap-2 transition">
                        <i data-lucide="youtube" class="w-4 h-4"></i> Ouvir no YouTube
                    </a>
                    <a id="modal-cifra" href="#" target="_blank" class="flex-1 bg-amber-500 hover:bg-amber-600 text-white text-xs font-semibold py-2.5 px-4 rounded-xl flex items-center justify-center gap-2 transition">
                        <i data-lucide="file-text" class="w-4 h-4"></i> Ver Cifra da Música
                    </a>
                </div>
            </div>

            <!-- Footer Modal -->
            <div class="border-t border-slate-100 p-4 bg-slate-50 flex justify-between items-center">
                <button id="modal-playlist-btn" onclick="" class="text-xs font-semibold text-indigo-600 hover:text-indigo-800 flex items-center gap-1">
                    <i data-lucide="plus-circle" class="w-4 h-4"></i> Adicionar à Seleção
                </button>
                <button onclick="closeSongModal()" class="px-4 py-2 bg-slate-200 hover:bg-slate-300 text-slate-700 text-xs font-semibold rounded-xl transition">
                    Fechar
                </button>
            </div>
        </div>
    </div>

    <!-- Modal Sobre -->
    <div id="about-modal" class="fixed inset-0 bg-slate-900/60 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-white w-full max-w-md rounded-3xl shadow-2xl p-6 space-y-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center gap-2">
                    <div class="p-2 gradient-bg rounded-xl text-white">
                        <i data-lucide="radio" class="w-5 h-5"></i>
                    </div>
                    <h3 class="font-bold text-slate-900">Sobre o Sintonizados</h3>
                </div>
                <button onclick="closeAboutModal()" class="text-slate-400 hover:text-slate-600">
                    <i data-lucide="x" class="w-5 h-5"></i>
                </button>
            </div>
            <p class="text-xs text-slate-600 leading-relaxed">
                O <strong>Sintonizados — Louvor & Palavra</strong> foi desenvolvido para líderes de louvor, pregadores, grupos de oração e cristãos em geral que desejam alinhar as músicas adoradas ao tema central da palavra ministrada.
            </p>
            <div class="bg-indigo-50 p-3 rounded-xl text-xs text-indigo-800 space-y-1">
                <p class="font-semibold">💡 Dica de Uso:</p>
                <p>Use a aba <strong>Sintonizador IA</strong> para digitar trechos de sermões, temas específicos ou até o seu momento devocional para receber recomendações teologicamente conectadas.</p>
            </div>
            <div class="pt-2 text-right">
                <button onclick="closeAboutModal()" class="px-4 py-2 gradient-bg text-white text-xs font-semibold rounded-xl">Entendi</button>
            </div>
        </div>
    </div>

    <!-- Mobile Bottom Navigation Bar -->
    <div class="md:hidden sticky bottom-0 z-40 bg-white border-t border-slate-200 flex items-center justify-around p-2">
        <button onclick="switchTab('explore')" id="mob-explore" class="flex flex-col items-center gap-1 text-slate-600 p-2 text-[10px] font-medium">
            <i data-lucide="compass" class="w-5 h-5"></i>
            <span>Temas</span>
        </button>
        <button onclick="switchTab('ai-search')" id="mob-ai-search" class="flex flex-col items-center gap-1 text-slate-600 p-2 text-[10px] font-medium">
            <i data-lucide="sparkles" class="w-5 h-5 text-amber-500"></i>
            <span>Sintonizador IA</span>
        </button>
        <button onclick="switchTab('playlist')" id="mob-playlist" class="flex flex-col items-center gap-1 text-slate-600 p-2 text-[10px] font-medium relative">
            <i data-lucide="list-music" class="w-5 h-5"></i>
            <span>Minha Seleção</span>
            <span id="mob-playlist-count" class="hidden absolute top-1 right-3 bg-indigo-600 text-white text-[9px] w-4 h-4 rounded-full flex items-center justify-center font-bold">0</span>
        </button>
    </div>

    <!-- JavaScript Principal -->
    <script>
        // Configurações Gemini API
        const apiKey = ""; // A chave é injetada em tempo de execução no ambiente

        // Banco de Dados Local de Temas e Louvores
        const DB_TOPICS = [
            { id: 'todos', label: 'Todas as Palavras', icon: 'layers' },
            { id: 'paz', label: 'Paz & Ansiedade', icon: 'sun' },
            { id: 'esperanca', label: 'Esperança & Fé', icon: 'anchor' },
            { id: 'gratidao', label: 'Gratidão & Agradecimento', icon: 'heart' },
            { id: 'vitoria', label: 'Vitória & Batalha', icon: 'shield-check' },
            { id: 'perdao', label: 'Perdão & Graça', icon: 'sparkle' },
            { id: 'presenca', label: 'Presença de Deus', icon: 'flame' },
            { id: 'cura', label: 'Cura & Restauração', icon: 'activity' }
        ];

        const DB_SONGS = [
            {
                id: '1',
                title: 'Acalma o Meu Coração',
                artist: 'Anderson Freire',
                topic: 'paz',
                bibleRef: 'Filipenses 4:6-7 / Mateus 11:28',
                explanation: 'Perfeito para pregações sobre ansiedade e descanso na soberania de Deus diante das tempestades da vida.',
                lyric: 'Acalma o meu coração, tu és a minha paz no meio da tempestade. Não me deixes desanimar...',
                youtube: 'https://www.youtube.com/results?search_query=Acalma+o+Meu+Coracao+Anderson+Freire',
                cifra: 'https://www.cifraclub.com.br/anderson-freire/acalma-o-meu-coracao/'
            },
            {
                id: '2',
                title: 'Aquietai-vos',
                artist: 'Ministério Zoe',
                topic: 'paz',
                bibleRef: 'Salmos 46:10',
                explanation: 'Diretamente alinhado com o comando de Salmos 46:10 para confiar que Ele é Deus e está no controle de tudo.',
                lyric: 'Sabei que Eu sou Deus, aquietai-vos e vede o que Eu vou fazer...',
                youtube: 'https://www.youtube.com/results?search_query=Aquietai-vos+Ministerio+Zoe',
                cifra: 'https://www.cifraclub.com.br/ministerio-zoe/aquietai-vos/'
            },
            {
                id: '3',
                title: 'Porque Ele Vive',
                artist: 'Harpa Cristã / Tradicional',
                topic: 'esperanca',
                bibleRef: 'João 14:19 / Romanos 8:31',
                explanation: 'Clássico para sermões sobre esperança no futuro, ressurreição e a certeza da vitória em Cristo Jesus.',
                lyric: 'Porque Ele vive, posso crer no amanhã. Porque Ele vive, temor não há!',
                youtube: 'https://www.youtube.com/results?search_query=Porque+Ele+Vive',
                cifra: 'https://www.cifraclub.com.br/harpa-crista/porque-ele-vive/'
            },
            {
                id: '4',
                title: 'Bondade de Deus',
                artist: 'Isaías Saad / Bethel Music',
                topic: 'gratidao',
                bibleRef: 'Salmos 23:6 / Lamentações 3:22-23',
                explanation: 'Ideal para momentos de gratidão pela fidelidade de Deus que se renova a cada manhã.',
                lyric: 'Tua bondade me seguirá, me seguirá, Senhor. Com minha vida e tudo o que sou, eu te adorarei...',
                youtube: 'https://www.youtube.com/results?search_query=Bondade+de+Deus+Isaias+Saad',
                cifra: 'https://www.cifraclub.com.br/isaias-saad/bondade-de-deus/'
            },
            {
                id: '5',
                title: 'O Escudo',
                artist: 'Voz da Verdade',
                topic: 'vitoria',
                bibleRef: 'Salmos 91 / Isaías 43:2',
                explanation: 'Inspirador para mensagens sobre livramento, proteção divina e superação de lutas espirituais e diárias.',
                lyric: 'Por que chorar, se a força que há em ti é maior que o mundo inteiro? Se o mar se abrir, tu passarás...',
                youtube: 'https://www.youtube.com/results?search_query=O+Escudo+Voz+da+Verdade',
                cifra: 'https://www.cifraclub.com.br/voz-da-verdade/o-escudo/'
            },
            {
                id: '6',
                title: 'Todavia Me Alegrarei',
                artist: 'Samuel Messias',
                topic: 'esperanca',
                bibleRef: 'Habacuque 3:17-18',
                explanation: 'A trilha ideal para palavras sobre confiar em Deus mesmo em tempos de escassez ou provação.',
                lyric: 'E ainda que a figueira não floresça, e não haja fruto na vide... Todavia me alegrarei no Deus da minha salvação.',
                youtube: 'https://www.youtube.com/results?search_query=Todavia+Me+Alegrarei+Samuel+Messias',
                cifra: 'https://www.cifraclub.com.br/samuel-messias/todavia-me-alegrarei/'
            },
            {
                id: '7',
                title: 'Graça',
                artist: 'Paulo César Baruk',
                topic: 'perdao',
                bibleRef: 'Efésios 2:8-9 / 2 Coríntios 12:9',
                explanation: 'Ideal para estudos sobre o favor imerecido de Deus e a redenção em Cristo.',
                lyric: 'Tua graça me basta, tua graça me alcança. Não pelo que fiz, mas pelo que Tu és...',
                youtube: 'https://www.youtube.com/results?search_query=Graca+Paulo+Cesar+Baruk',
                cifra: 'https://www.cifraclub.com.br/paulo-cesar-baruk/graca/'
            },
            {
                id: '8',
                title: 'Ruja o Leão',
                artist: 'Talita Catanzaro / Dunamis',
                topic: 'presenca',
                bibleRef: 'Apocalipse 5:5 / Joel 3:16',
                explanation: 'Excelente para louvor corporativo sobre a majestade, poder e manifestação da glória do Leão de Judá.',
                lyric: 'Que o céu se abra e o Teu reino venha. Ruja o Leão, que a terra trema diante do Rei!',
                youtube: 'https://www.youtube.com/results?search_query=Ruja+o+Leao',
                cifra: 'https://www.cifraclub.com.br/dunamis-music/ruja-o-leao/'
            },
            {
                id: '9',
                title: 'Restaura o Meu Ser',
                artist: 'Kester',
                topic: 'cura',
                bibleRef: 'Salmos 51:10 / Jeremias 17:14',
                explanation: 'Indicado para apelos de conversão, restauração de casamentos e renovação do homem interior.',
                lyric: 'Restaura o meu ser, renova a minha mente. Faz de mim um vaso novo em tuas mãos...',
                youtube: 'https://www.youtube.com/results?search_query=Restaura+o+Meu+Ser',
                cifra: 'https://www.cifraclub.com.br/kester/restaura-o-meu-ser/'
            }
        ];

        // Estado da Aplicação
        let currentTopic = 'todos';
        let userPlaylist = [];

        // Inicialização
        document.addEventListener('DOMContentLoaded', () => {
            lucide.createIcons();
            loadTopics();
            renderSongs();
            loadPlaylistFromStorage();
        });

        // Alternância de Abas
        function switchTab(tabId) {
            const tabs = ['explore', 'ai-search', 'playlist'];
            tabs.forEach(t => {
                const el = document.getElementById(`tab-${t}`);
                const navBtn = document.getElementById(`nav-${t}`);
                const mobBtn = document.getElementById(`mob-${t}`);

                if (t === tabId) {
                    el.classList.remove('hidden');
                    if (navBtn) navBtn.classList.add('bg-white', 'shadow-sm', 'text-indigo-600');
                    if (mobBtn) mobBtn.classList.add('text-indigo-600');
                } else {
                    el.classList.add('hidden');
                    if (navBtn) navBtn.classList.remove('bg-white', 'shadow-sm', 'text-indigo-600');
                    if (mobBtn) mobBtn.classList.remove('text-indigo-600');
                }
            });
        }

        // Renderizar Tópicos
        function loadTopics() {
            const container = document.getElementById('topics-grid');
            container.innerHTML = DB_TOPICS.map(t => `
                <button onclick="selectTopic('${t.id}')" id="btn-topic-${t.id}" class="p-3.5 rounded-2xl border text-left transition flex flex-col justify-between h-24 ${t.id === currentTopic ? 'bg-indigo-600 border-indigo-600 text-white shadow-md shadow-indigo-200' : 'bg-white border-slate-200 text-slate-700 hover:border-indigo-300 hover:bg-indigo-50/30'}">
                    <i data-lucide="${t.icon}" class="w-5 h-5 mb-2 ${t.id === currentTopic ? 'text-white' : 'text-indigo-600'}"></i>
                    <span class="text-xs font-semibold leading-snug">${t.label}</span>
                </button>
            `).join('');
            lucide.createIcons();
        }

        // Selecionar Tópico
        function selectTopic(topicId) {
            currentTopic = topicId;
            loadTopics();
            renderSongs();

            const topicObj = DB_TOPICS.find(t => t.id === topicId);
            document.getElementById('current-topic-title').innerText = topicObj ? topicObj.label : 'Louvores';
        }

        // Renderizar Músicas no Explorar
        function renderSongs() {
            const container = document.getElementById('songs-list');
            const filtered = currentTopic === 'todos' 
                ? DB_SONGS 
                : DB_SONGS.filter(s => s.topic === currentTopic);

            document.getElementById('songs-count').innerText = `${filtered.length} louvor(es)`;

            if (filtered.length === 0) {
                container.innerHTML = `
                    <div class="col-span-full text-center py-12 bg-white rounded-2xl border border-slate-200 p-6">
                        <p class="text-slate-500 text-sm">Nenhum louvor pré-cadastrado para este tema. Experimente usar a <strong>Aba de IA</strong> para gerar louvores sob medida!</p>
                    </div>
                `;
                return;
            }

            container.innerHTML = filtered.map(song => renderSongCard(song)).join('');
            lucide.createIcons();
        }

        // Template do Card de Louvor
        function renderSongCard(song) {
            const inPlaylist = userPlaylist.some(item => item.id === song.id || item.title === song.title);
            return `
                <div class="glass-card p-5 rounded-2xl hover:shadow-lg transition-all border border-slate-200 flex flex-col justify-between group">
                    <div class="space-y-3">
                        <div class="flex items-start justify-between gap-2">
                            <div>
                                <span class="text-[10px] font-bold uppercase tracking-wider text-indigo-600 bg-indigo-50 px-2.5 py-0.5 rounded-full border border-indigo-100">${getTopicLabel(song.topic)}</span>
                                <h4 class="text-lg font-bold text-slate-900 mt-1 group-hover:text-indigo-600 transition-colors font-serif-title">${song.title}</h4>
                                <p class="text-xs font-medium text-slate-500">${song.artist}</p>
                            </div>
                            <button onclick="togglePlaylist('${song.id}', '${escapeQuotes(song.title)}', '${escapeQuotes(song.artist)}', '${escapeQuotes(song.bibleRef)}', '${escapeQuotes(song.explanation)}', '${escapeQuotes(song.lyric)}', '${song.youtube}', '${song.cifra}', '${song.topic}')" 
                                class="p-2 rounded-xl transition ${inPlaylist ? 'bg-indigo-600 text-white' : 'bg-slate-100 text-slate-600 hover:bg-indigo-50 hover:text-indigo-600'}">
                                <i data-lucide="${inPlaylist ? 'check' : 'plus'}" class="w-4 h-4"></i>
                            </button>
                        </div>

                        <div class="bg-indigo-50/50 p-2.5 rounded-xl border border-indigo-100 text-xs">
                            <span class="font-bold text-indigo-900 block mb-0.5">📖 Versículo: ${song.bibleRef}</span>
                            <p class="text-slate-600 text-[11px] line-clamp-2">${song.explanation}</p>
                        </div>
                    </div>

                    <div class="pt-4 mt-2 border-t border-slate-100 flex items-center justify-between">
                        <button onclick="openSongModal('${song.title}', '${song.artist}', '${song.bibleRef}', '${escapeQuotes(song.explanation)}', '${escapeQuotes(song.lyric)}', '${song.youtube}', '${song.cifra}', '${getTopicLabel(song.topic)}')" 
                            class="text-xs font-semibold text-indigo-600 hover:text-indigo-800 flex items-center gap-1">
                            Ver Letra & Detalhes <i data-lucide="chevron-right" class="w-3.5 h-3.5"></i>
                        </button>
                    </div>
                </div>
            `;
        }

        // Modal de Louvor
        function openSongModal(title, artist, bibleRef, explanation, lyric, youtube, cifra, topicLabel) {
            document.getElementById('modal-title').innerText = title;
            document.getElementById('modal-artist').innerText = artist;
            document.getElementById('modal-bible-ref').innerText = bibleRef;
            document.getElementById('modal-explanation').innerText = explanation;
            document.getElementById('modal-lyric').innerText = `"${lyric}"`;
            document.getElementById('modal-tag').innerText = topicLabel || 'Louvor';
            document.getElementById('modal-youtube').href = youtube;
            document.getElementById('modal-cifra').href = cifra;

            document.getElementById('song-modal').classList.remove('hidden');
        }

        function closeSongModal() {
            document.getElementById('song-modal').classList.add('hidden');
        }

        // Modal Sobre
        function openAboutModal() { document.getElementById('about-modal').classList.remove('hidden'); }
        function closeAboutModal() { document.getElementById('about-modal').classList.add('hidden'); }

        // Util para buscar Label do Tema
        function getTopicLabel(topicId) {
            const found = DB_TOPICS.find(t => t.id === topicId);
            return found ? found.label : 'Palavra & Louvor';
        }

        function escapeQuotes(str) {
            return (str || '').replace(/'/g, "\\'").replace(/"/g, '&quot;');
        }

        // Gerenciamento da Seleção/Playlist
        function togglePlaylist(id, title, artist, bibleRef, explanation, lyric, youtube, cifra, topic) {
            const index = userPlaylist.findIndex(item => item.title === title);
            if (index >= 0) {
                userPlaylist.splice(index, 1);
            } else {
                userPlaylist.push({ id, title, artist, bibleRef, explanation, lyric, youtube, cifra, topic });
            }
            savePlaylistToStorage();
            renderSongs();
            renderPlaylist();
        }

        function renderPlaylist() {
            const countEl = document.getElementById('playlist-count');
            const mobCountEl = document.getElementById('mob-playlist-count');
            const emptyEl = document.getElementById('playlist-empty');
            const itemsEl = document.getElementById('playlist-items');
            const clearBtn = document.getElementById('btn-clear-playlist');

            const count = userPlaylist.length;

            if (count > 0) {
                countEl.innerText = count;
                countEl.classList.remove('hidden');
                mobCountEl.innerText = count;
                mobCountEl.classList.remove('hidden');
                emptyEl.classList.add('hidden');
                clearBtn.classList.remove('hidden');

                itemsEl.innerHTML = userPlaylist.map(song => `
                    <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm space-y-3">
                        <div class="flex justify-between items-start">
                            <div>
                                <h4 class="font-bold text-slate-900 font-serif-title">${song.title}</h4>
                                <p class="text-xs text-slate-500">${song.artist}</p>
                            </div>
                            <button onclick="togglePlaylist('${song.id}', '${escapeQuotes(song.title)}')" class="text-slate-400 hover:text-rose-600 p-1">
                                <i data-lucide="trash-2" class="w-4 h-4"></i>
                            </button>
                        </div>
                        <p class="text-xs text-indigo-900 bg-indigo-50 p-2 rounded-lg font-medium">📖 ${song.bibleRef}</p>
                        <div class="flex gap-2">
                            <a href="${song.youtube}" target="_blank" class="text-[11px] bg-red-50 text-red-600 px-2.5 py-1.5 rounded-lg flex items-center gap-1 font-semibold">
                                <i data-lucide="youtube" class="w-3.5 h-3.5"></i> Ouvir
                            </a>
                            <a href="${song.cifra}" target="_blank" class="text-[11px] bg-amber-50 text-amber-700 px-2.5 py-1.5 rounded-lg flex items-center gap-1 font-semibold">
                                <i data-lucide="file-text" class="w-3.5 h-3.5"></i> Cifra
                            </a>
                        </div>
                    </div>
                `).join('');
            } else {
                countEl.classList.add('hidden');
                mobCountEl.classList.add('hidden');
                emptyEl.classList.remove('hidden');
                clearBtn.classList.add('hidden');
                itemsEl.innerHTML = '';
            }
            lucide.createIcons();
        }

        function clearPlaylist() {
            userPlaylist = [];
            savePlaylistToStorage();
            renderPlaylist();
            renderSongs();
        }

        function savePlaylistToStorage() {
            // Em conformidade com o ambiente Canvas
            try {
                window.playlistData = userPlaylist;
            } catch(e){}
        }

        function loadPlaylistFromStorage() {
            try {
                if (window.playlistData) {
                    userPlaylist = window.playlistData;
                    renderPlaylist();
                }
            } catch(e){}
        }

        // Função de Ajuda para IA
        function setAiExample(text) {
            document.getElementById('ai-input').value = text;
        }

        // API GEMINI: Recomendações em Tempo Real
        async function generateAiRecommendations() {
            const input = document.getElementById('ai-input').value.trim();
            if (!input) {
                alert('Por favor, digite um tema, palavra ou versículo para sintonizar os louvores.');
                return;
            }

            const loadingEl = document.getElementById('ai-loading');
            const resultsEl = document.getElementById('ai-results');
            const btnSubmit = document.getElementById('btn-ai-submit');

            loadingEl.classList.remove('hidden');
            resultsEl.innerHTML = '';
            btnSubmit.disabled = true;

            const systemPrompt = `Você é um assistente teológico e especialista em louvores/músicas cristãs congregacionais do Brasil. 
Sua tarefa é ler um tema, versículo ou resumo de mensagem e recomendar EXATAMENTE 3 a 4 louvores evangélicos conhecidos no meio cristão brasileiro que se encaixem perfeitamente.

Responda EXCLUSIVAMENTE em formato JSON com o seguinte esquema:
{
  "summary": "Breve reflexão espiritual ligando o tema digitado com a adoração (máximo 2 frases)",
  "songs": [
    {
      "title": "Nome da Música",
      "artist": "Cantor ou Ministério",
      "bibleRef": "Versículo bíblico principal de conexão",
      "explanation": "Por que esta música conecta com esta palavra ministrada",
      "lyric": "Trecho marcante e conhecido do refrão",
      "topic": "paz|esperanca|gratidao|vitoria|perdao|presenca|cura"
    }
  ]
}`;

            const userQuery = `Tema / Palavra digitada pelo líder: "${input}"`;

            let retries = 0;
            const delays = [1000, 2000, 4000, 8000, 16000];

            async function makeApiCall() {
                try {
                    const response = await fetch(`https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent?key=${apiKey}`, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify({
                            contents: [{ parts: [{ text: userQuery }] }],
                            systemInstruction: { parts: [{ text: systemPrompt }] },
                            generationConfig: {
                                responseMimeType: "application/json"
                            }
                        })
                    });

                    if (!response.ok) throw new Error(`HTTP error! status: ${response.status}`);
                    
                    const data = await response.json();
                    const text = data.candidates?.[0]?.content?.parts?.[0]?.text;
                    if (!text) throw new Error("Resposta inválida da IA");

                    const parsedData = JSON.parse(text);
                    displayAiResults(parsedData);

                } catch (error) {
                    if (retries < delays.length) {
                        const delay = delays[retries];
                        retries++;
                        setTimeout(makeApiCall, delay);
                    } else {
                        loadingEl.classList.add('hidden');
                        btnSubmit.disabled = false;
                        resultsEl.innerHTML = `
                            <div class="bg-rose-50 border border-rose-200 text-rose-700 p-4 rounded-2xl text-xs text-center">
                                Não foi possível sintonizar as recomendações no momento. Por favor, tente novamente em instantes.
                            </div>
                        `;
                    }
                }
            }

            makeApiCall();
        }

        function displayAiResults(data) {
            const loadingEl = document.getElementById('ai-loading');
            const resultsEl = document.getElementById('ai-results');
            const btnSubmit = document.getElementById('btn-ai-submit');

            loadingEl.classList.add('hidden');
            btnSubmit.disabled = false;

            let html = `
                <div class="bg-indigo-50 border border-indigo-200 p-4 rounded-2xl text-xs text-indigo-900 mb-4">
                    <p class="font-bold flex items-center gap-1.5 mb-1 text-indigo-950">
                        <i data-lucide="sparkles" class="w-4 h-4 text-amber-500"></i> Reflexão de Sintonização:
                    </p>
                    <p class="leading-relaxed text-indigo-800">${data.summary}</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
            `;

            data.songs.forEach((song, idx) => {
                const songId = `ai-${Date.now()}-${idx}`;
                const youtubeUrl = `https://www.youtube.com/results?search_query=${encodeURIComponent(song.title + ' ' + song.artist)}`;
                const cifraUrl = `https://www.cifraclub.com.br/?q=${encodeURIComponent(song.title + ' ' + song.artist)}`;

                html += renderSongCard({
                    id: songId,
                    title: song.title,
                    artist: song.artist,
                    bibleRef: song.bibleRef,
                    explanation: song.explanation,
                    lyric: song.lyric,
                    youtube: youtubeUrl,
                    cifra: cifraUrl,
                    topic: song.topic || 'presenca'
                });
            });

            html += `</div>`;
            resultsEl.innerHTML = html;
            lucide.createIcons();
        }
    </script>
</body>
</html>

