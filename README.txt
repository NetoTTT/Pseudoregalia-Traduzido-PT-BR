PSEUDOREGALIA - TRADUCAO PT-BR
==============================

Versao: 1.0
Idioma: Portugues BR
Jogo: Pseudoregalia
Traducao: Assistida por IA

Traducao nao-oficial para Portugues Brasileiro do jogo Pseudoregalia, desenvolvido pela rittzler.

---------------------------------------------------------

SOBRE O PROJETO

Este projeto traduz Pseudoregalia para o Portugues Brasileiro, cobrindo:

- Dialogos dos NPCs: todas as falas do jogo
- Notas e lore: textos de lore espalhados pelo mapa
- Interface (UI): menus, pause, opcoes, creditos, tela de titulo
- Upgrades e roupas: descricoes de habilidades e outfits

A traducao foi gerada com auxilio de Inteligencia Artificial e revisada manualmente.

---------------------------------------------------------

LIMITACAO: SEM ACENTOS

O jogo utiliza uma fonte customizada que suporta apenas caracteres ASCII (letras sem acento). Por isso, a traducao nao exibe acentos, cedilhas ou til - mas o texto permanece completamente legivel.

Exemplos:
- Options -> Opcoes
- Credits -> Creditos
- Continue -> Continuar
- "a dimly lit corridor..." -> "um corredor mal iluminado..."

Isso e uma limitacao tecnica do jogo, nao um erro da traducao.

---------------------------------------------------------

TUTORIAL DE INSTALACAO

Passo 1 - Localize a pasta do jogo
1. Abra a Steam.
2. Va ate sua Biblioteca de jogos.
3. Clique com o botao direito em Pseudoregalia.
4. Selecione Gerenciar -> Explorar arquivos locais.
5. Navegue ate a pasta: pseudoregalia\Content\Paks\

Passo 2 - Copie o arquivo de traducao
1. Baixe o arquivo "pseudoregalia-PTBR_P.pak" deste repositorio.
2. Cole-o dentro da pasta Paks\ do jogo.

O resultado final deve ser assim:
pseudoregalia\Content\Paks\
    pseudoregalia-WindowsNoEditor.pak   <-- arquivo original (nao mexa)
    pseudoregalia-PTBR_P.pak           <-- traducao (adicione este)

O sufixo _P faz o Unreal Engine carregar este arquivo por cima do original, sem modificar nada do jogo base.

Passo 3 - Jogue!
Abra o jogo normalmente pela Steam. Os textos ja aparecem em Portugues Brasileiro.

---------------------------------------------------------

RESUMO RAPIDO
1. Abra a pasta do jogo pela Steam -> pseudoregalia\Content\Paks\
2. Cole "pseudoregalia-PTBR_P.pak" nessa pasta
3. Jogue!

Para desinstalar: delete o arquivo "pseudoregalia-PTBR_P.pak". O jogo volta ao ingles automaticamente.

---------------------------------------------------------

TRADUCAO POR IA - PODE HAVER ERROS

Esta traducao foi gerada por um modelo de linguagem local e nao foi revisada por um tradutor humano profissional. Isso significa que:

- Algumas frases podem soar estranhas ou literais demais
- Termos de gameplay e habilidades foram mantidos em ingles intencionalmente (Dream Breaker, Sun Greaves, Cling Gem, etc.)
- Nomes proprios (Sybil, Princess) tambem nao foram traduzidos
- Pode haver ocasionalmente erros de contexto ou de genero gramatical

Se encontrar algum erro, toda ajuda e bem-vinda!

---------------------------------------------------------

REPORTAR ERROS E BUGS

Encontrou uma traducao estranha, texto em ingles que deveria estar traduzido, ou qualquer outro problema? Por favor, abra uma Issue no GitHub do projeto com detalhes sobre o local, o texto original e uma sugestao de correcao.

---------------------------------------------------------

FAQ

O jogo continua em ingles apos instalar o .pak?
Verifique se o arquivo esta na pasta correta: pseudoregalia\Content\Paks\ e se o nome termina em _P.pak.

Por que nao tem acentos?
O jogo usa uma fonte customizada ASCII-only. Adicionar acentos causa crash no jogo.

Como desfaco a traducao?
Delete "pseudoregalia-PTBR_P.pak" da pasta Paks\. O jogo volta ao ingles automaticamente.

---------------------------------------------------------

AVISO LEGAL

Este e um projeto nao-oficial feito por fas, sem afiliacao com rittzler (desenvolvedor do jogo). Pseudoregalia e todos os seus conteudos sao propriedade de seus respectivos criadores. Este projeto nao distribui nenhum arquivo do jogo original.

---------------------------------------------------------

CREDITOS

- Traducao: NetoTTT (com auxilio de IA)
- Jogo Original: rittzler
- Ferramentas: UAssetAPI, repak
- Codigo-fonte da pipeline de traducao: ue5-pak-translator (GitHub)
