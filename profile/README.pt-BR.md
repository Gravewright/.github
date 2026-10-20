# Gravewright

**Seu mundo. Seu grupo. Sua próxima grande sessão.**

[English](https://github.com/Gravewright/.github/blob/main/profile/README.md) · [Português (Brasil)](https://github.com/Gravewright/.github/blob/main/profile/README.pt-BR.md)

O Gravewright é uma mesa virtual universal para campanhas de RPG, gratuita, open
source e hospedada por você. Prepare mapas, reúna o grupo pelo navegador e tenha
tokens, fichas, dados e anotações da campanha em um mundo que você controla.

**[Conheça o Gravewright](https://gravewright.com/pt-br.html)** · [Baixar](https://github.com/Gravewright/gravewright/releases/latest) · [Primeiros passos](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/getting-started.md)

### Um lugar para sua campanha

- **Crie a atmosfera.** Prepare cenas com iluminação, névoa, paredes, áudio e efeitos visuais. Revele o mundo no seu ritmo.
- **Traga seus personagens.** Use fichas PDF ou um sistema de jogo independente, com personagens conectados aos tokens no tabuleiro.
- **Mantenha o ritmo da sessão.** Role dados, compartilhe anotações, compre cartas e acompanhe o combate sem sair da mesa.
- **Leve a história adiante.** Mantenha diários, missões, materiais e descobertas juntos entre as sessões.
- **Deixe a mesa com a sua cara.** Hospede sua instalação e adicione sistemas e módulos pelo Marketplace.

### Comece sua primeira mesa

Baixe o [ZIP completo da 0.3.0 e seu checksum](https://github.com/Gravewright/gravewright/releases/tag/v0.3.0),
extraia em uma pasta gravável e execute o instalador da sua plataforma:

| Plataforma | Instalador | Iniciar a mesa |
| --- | --- | --- |
| [Windows 10 (1803+) / 11, x64](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/pt-BR/windows-runner.md) | `Install Windows.bat` | `Gravewright Runner.bat` |
| [Linux, x64 / ARM64](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/pt-BR/linux-runner.md) | `bash "./Install Linux.sh"` | `bash "./Gravewright Runner.sh"` |
| [macOS 13.5+, Intel / Apple Silicon](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/pt-BR/macos-runner.md) | `Install macOS.command` | `Gravewright Runner.command` |

O instalador prepara ferramentas, dependências e configurações e cria seu Runner.
Abra-o, crie a conta de administrador pelo navegador e comece sua campanha.
Ferramentas e pacotes ausentes precisam de internet; consulte os requisitos no
guia de cada plataforma. Configuração, dados da campanha e ferramentas gerenciadas
ficam por padrão dentro da instalação extraída.

O Runner inicia localmente no seu computador. Para convidar jogadores pela rede
ou pela internet, siga o [guia de hospedagem](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/pt-BR/deployment.md).
Os dados da campanha ficam sob seu controle.

### Disponível: Gravewright 0.3.0 Alpha

A versão **0.3.0 Alpha** traz criação de mapas, automação visual e intercâmbio
de mapas para a mesa:

- **Map Builder.** Construa com tiles ou pintura de terreno, organize camadas nomeadas, importe suas imagens e mantenha projetos editáveis com salvamento automático e recuperação.
- **Objetos Inteligentes.** Conecte portas, alavancas, tochas e regiões a comportamentos visuais com eventos, condições e ações.
- **Importação e exportação de mapas.** Importe uma imagem pronta como fundo do Builder, ou arquivos `.uvtt`, `.dd2vtt` e `.df2vtt` como cenas nativas com paredes, portas e luzes suportadas. Exporte uma cópia compatível da cena nativa atual.
- **Prepare antes de compartilhar.** Gere uma cena privada e aplique novas edições do projeto com **Atualizar cena**. Ativar a cena para os jogadores continua sendo uma ação separada.

Uma imagem pronta não reconstrói suas camadas originais; a importação Universal
VTT cria cenas nativas, não projetos do Builder. O VTT oferece ferramentas
genéricas de campanha; os sistemas instalados continuam responsáveis pelas
regras de cada jogo.

**[Baixe o Gravewright 0.3.0 Alpha](https://github.com/Gravewright/gravewright/releases/tag/v0.3.0)** ·
[Novidades da versão](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/releases/0.3.0.md) ·
[Guia do Map Builder](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/pt-BR/map-builder.md) ·
[Guia do Universal VTT](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/pt-BR/universal-vtt.md)

O Gravewright segue em desenvolvimento Alpha. A 0.3.0 acrescenta migrações de
banco: faça backup das campanhas existentes e siga as
[instruções de atualização](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/releases/0.3.0.md#download-e-atualização).
Consulte os fluxos disponíveis no
[guia de uso](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/pt-BR/user-guide.md).

### Escolha como jogar

Use mapas, tokens, dados, diários e cartas para conduzir a campanha. Com o
**PDF System** incluído, traga uma ficha conhecida, mapeie seus campos e vincule
o personagem a um token. Fichas dedicadas e automações de regras vêm de sistemas
independentes; a cobertura depende do sistema instalado.

Escolha sistemas e módulos pelo
[Marketplace assinado](https://github.com/Gravewright/marketplace) ou use as APIs
documentadas para criar ferramentas para o seu grupo.

O **[Translator 0.1.2](https://github.com/Gravewright/marketplace/releases/tag/gravewright.translator-v0.1.2)**
permite que cada jogador escolha inglês, português brasileiro ou espanhol para a
interface compatível. Inglês é o padrão. Módulos independentes podem usar a mesma
API oficial de tradução; nomes e histórias escritos pelo seu grupo permanecem como vocês criaram.

### Encontre suas ferramentas

| Projeto | O que leva para sua mesa |
| --- | --- |
| [Gravewright VTT](https://github.com/Gravewright/gravewright) | A mesa virtual, guias de instalação e APIs de integração. |
| [Marketplace](https://github.com/Gravewright/marketplace) | Releases assinadas de módulos e sistemas. |
| [3D Dice](https://github.com/Gravewright/Gravewright-3D-Dice) | Dados 3D para suas rolagens. |
| [Translator](https://github.com/Gravewright/translator) | Localização oficial da interface e API de tradução compartilhada para módulos independentes. |
| [DnD 5e SRD](https://github.com/Gravewright/dnd-srd-5e) | Um pacote de sistema: [0.1.2](https://github.com/Gravewright/dnd-srd-5e/releases/tag/v0.1.2), com regras 2014/SRD 5.1 e 2024/SRD 5.2.1, fichas, compêndios e automações de combate. |
| [Savage Worlds Compatibility Package for Gravewright](https://github.com/Gravewright/Savage-Worlds-Compatibility-Package-for-Gravewright) | Um pacote de sistema com fichas editáveis de personagens e NPCs, 13 modelos vazios de itens e automações SWADE: [0.1.2](https://github.com/Gravewright/Savage-Worlds-Compatibility-Package-for-Gravewright/releases/tag/v0.1.2). |

Os compêndios parciais do exemplo DnD permanecem em inglês. O guia da **0.1.2**
documenta a instalação no **VTT 0.2.3**: instale o único pacote de sistema em
**Sistemas** e selecione-o para sua mesa. Fichas, compêndios e automações ficam
juntos; o mestre avança o combate pela mesa. Veja o
[guia de instalação e os limites de automação](https://github.com/Gravewright/dnd-srd-5e/blob/main/README.pt-BR.md).

O pacote gratuito de Savage Worlds não inclui compêndios nem textos do livro.
O guia da **0.1.2** documenta a instalação no **VTT 0.2.3** por **Sistemas** e pelo
Marketplace assinado. Selecione o pacote completo do sistema para a mesa. Fichas,
modelos, arquivos e automações ficam dentro desse sistema; o mestre avança o
combate pela mesa. Escolha ou crie um baralho de ação
nativo em **Extensões → Savage Worlds → Personalizar**, com três estilos originais disponíveis.
A interface oferece inglês, português brasileiro e espanhol pelo Translator oficial.
Veja o [guia de instalação SWADE](https://github.com/Gravewright/Savage-Worlds-Compatibility-Package-for-Gravewright/blob/main/README.pt-BR.md).

Os guias dos sistemas documentam as versões compatíveis do host; confira-os antes de atualizar um sistema ou o VTT.

### Ajude a preparar a próxima sessão

Conte como o Gravewright funciona na sua mesa, [relate um problema](https://github.com/Gravewright/gravewright/issues)
ou ajude com traduções, acessibilidade e documentação. Desenvolvedores podem
[criar integrações](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/api.md)
e [desenvolver módulos](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/modules.md).
Consulte o [guia de contribuição](https://github.com/Gravewright/gravewright/blob/main/CONTRIBUTING.pt-BR.md)
e a [política de segurança](https://github.com/Gravewright/gravewright/blob/main/SECURITY.pt-BR.md).

O núcleo usa **GPL-3.0-only** com uma
[permissão para módulos independentes](https://github.com/Gravewright/gravewright/blob/main/LICENSE-EXCEPTION.pt-BR.md).
Módulos escritos de forma independente podem usar qualquer licença, inclusive
proprietária. Cópias e modificações da implementação do núcleo continuam sujeitas
à licença dele. Consulte a [política de licenciamento](https://github.com/Gravewright/gravewright/blob/main/LICENSING.pt-BR.md)
e os [avisos de terceiros](https://github.com/Gravewright/gravewright/blob/main/THIRD_PARTY_NOTICES.pt-BR.md).
