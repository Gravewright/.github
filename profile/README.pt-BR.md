# Gravewright

**Uma mesa virtual para jogar RPG pelo navegador, hospedada por você.**

[English](https://github.com/Gravewright/.github/blob/main/profile/README.md) · [Português (Brasil)](https://github.com/Gravewright/.github/blob/main/profile/README.pt-BR.md)

Prepare seus mundos, reúna os jogadores e conduza suas sessões com mapas, fichas PDF e ferramentas de mesa em tempo real. O Gravewright é open source, com um núcleo extensível e documentação para usuários e desenvolvedores.

### Comece a jogar

**[Baixar Alpha 0.1.0](https://github.com/Gravewright/gravewright/releases/tag/v0.1.0-alpha.0)** · [Código-fonte](https://github.com/Gravewright/gravewright) · [Documentação](https://github.com/Gravewright/gravewright/blob/main/docs/README.pt-BR.md)

No Windows, baixe o ZIP completo do projeto na release, extraia para uma pasta com permissão de escrita e dê dois cliques em **`Gravewright Runner.bat`**. O Runner verifica uv, Python e Node.js/npm, instala ferramentas e dependências ausentes, compila o frontend e abre a aplicação no navegador. Quando possível, cria um atalho com o ícone do projeto ao lado do executor.

O Runner requer Windows 10 versão 1803 ou superior, ou Windows 11, em x64. Os downloads exigem internet. Os dados das campanhas ficam em `%LOCALAPPDATA%\Gravewright\data`, separados do código. Esse perfil funciona no computador local; para receber jogadores pela rede, siga o guia de implantação.

### Na mesa

- **Campanhas e jogadores:** contas, convites, permissões de acesso e transmissão de cenas.
- **Mapas e cenas:** grades, tokens, paredes, névoa, iluminação, medição, desenhos, pings e efeitos.
- **Personagens:** atores, fichas PDF e mapeamento de campos pelo sistema nativo Gravewright PDF System.
- **Ferramentas de sessão:** chat em tempo real, dados, diários, missões, áudio, cartas, combate e compêndios.
- **Extensões:** manifests de módulos, hooks de ciclo de vida e interfaces Python, HTTP, WebSocket e de navegador documentadas.

Alpha 0.1.0 é a release atual. A interface da aplicação suporta inglês; a documentação do projeto está disponível em inglês e português brasileiro. Consulte os fluxos suportados e as limitações atuais no [guia de uso](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/user-guide.md).

### Explore e contribua

| Recurso | Por onde começar |
| --- | --- |
| Instalação e primeiro acesso | [Primeiros passos](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/getting-started.md) |
| Executor Windows e backups | [Guia do Runner](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/windows-runner.md) |
| Hospedagem pela rede e HTTPS | [Implantação](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/deployment.md) |
| Estrutura do código | [Arquitetura](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/architecture.md) e [mapa do código](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/code-map.md) |
| Integrações e extensões | [Guia de APIs](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/api.md) e [guia de módulos](https://github.com/Gravewright/gravewright/blob/main/docs/pt-BR/modules.md) |
| Bugs e propostas de funcionalidades | [Issues](https://github.com/Gravewright/gravewright/issues) |
| Código, documentação e traduções | [Como contribuir](https://github.com/Gravewright/gravewright/blob/main/CONTRIBUTING.pt-BR.md) |
| Relatos de vulnerabilidades | [Política de segurança](https://github.com/Gravewright/gravewright/blob/main/SECURITY.pt-BR.md) |

### Open source e módulos independentes

O núcleo do Gravewright usa **GPL-3.0-only**, com a [permissão para módulos independentes](https://github.com/Gravewright/gravewright/blob/main/LICENSE-EXCEPTION.pt-BR.md) sob a seção 7. Módulos de terceiros escritos independentemente podem usar **qualquer licença, inclusive proprietária**, utilizando ou não as APIs fornecidas. Cópias e modificações da implementação do núcleo continuam sujeitas à licença dele.

Dependências, recursos herdados e conteúdo dos usuários mantêm seus próprios termos aplicáveis. Consulte a [política de licenciamento](https://github.com/Gravewright/gravewright/blob/main/LICENSING.pt-BR.md) e os [avisos de terceiros](https://github.com/Gravewright/gravewright/blob/main/THIRD_PARTY_NOTICES.pt-BR.md).
