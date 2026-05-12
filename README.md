# <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Flag_of_Brazil.svg" width="28" height="28" alt="BR"> Pseudoregalia — Tradução PT-BR

![Status](https://img.shields.io/badge/Versão-1.0-blue)
![Idioma](https://img.shields.io/badge/Idioma-Português%20BR-green)
![Jogo](https://img.shields.io/badge/Jogo-Pseudoregalia-8b5cf6)
![IA](https://img.shields.io/badge/Tradução-Assistida%20por%20IA-orange)

Tradução não-oficial para **Português Brasileiro** do jogo **Pseudoregalia**, desenvolvido pela **rittzler**.

---

## <img src="assets/icons/book.svg" width="22" height="22" alt="Sobre"> Sobre o Projeto

Este projeto traduz **Pseudoregalia** para o Português Brasileiro, cobrindo:

- **Diálogos dos NPCs** — todas as falas do jogo
- **Notas e lore** — textos de lore espalhados pelo mapa
- **Interface (UI)** — menus, pause, opções, créditos, tela de título
- **Upgrades e roupas** — descrições de habilidades e outfits

A tradução foi gerada com auxílio de **Inteligência Artificial** e revisada manualmente.

---

## <img src="assets/icons/att.svg" width="22" height="22" alt="Limitação"> Limitação: Sem Acentos

O jogo utiliza uma **fonte customizada** que suporta apenas caracteres **ASCII** (letras sem acento). Por isso, a tradução não exibe acentos, cedilhas ou til — mas o texto permanece completamente legível:

| Original | Tradução |
|----------|----------|
| Options | Opcoes |
| Credits | Creditos |
| Continue | Continuar |
| *"a dimly lit corridor..."* | *"um corredor mal iluminado..."* |

Isso é uma **limitação técnica do jogo**, não um erro da tradução.

---

## <img src="assets/icons/download.svg" width="22" height="22" alt="Instalação"> Tutorial de Instalação

### Passo 1 — Localize a pasta do jogo

1. Abra a **Steam**.
2. Vá até sua **Biblioteca** de jogos.
3. Clique com o **botão direito** em **Pseudoregalia**.
4. Selecione **Gerenciar** → **Explorar arquivos locais**.
5. Navegue até a pasta:
   ```
   pseudoregalia\Content\Paks\
   ```

### Passo 2 — Copie o arquivo de tradução

1. Baixe o arquivo **`pseudoregalia-PTBR_P.pak`** deste repositório.
2. **Cole-o** dentro da pasta `Paks\` do jogo.

O resultado final deve ser assim:
```
pseudoregalia\Content\Paks\
    pseudoregalia-WindowsNoEditor.pak   ← arquivo original (não mexa)
    pseudoregalia-PTBR_P.pak           ← tradução (adicione este)
```

> O sufixo `_P` faz o Unreal Engine carregar este arquivo **por cima** do original, sem modificar nada do jogo base.

### Passo 3 — Jogue! <img src="assets/icons/gamepad.svg" width="20" height="20" alt="Jogue">

Abra o jogo normalmente pela Steam. Os textos já aparecem em Português Brasileiro.

---

## <img src="assets/icons/clipboard.svg" width="22" height="22" alt="Resumo"> Resumo Rápido

| Etapa | Ação |
|-------|------|
| **1** | Abra a pasta do jogo pela Steam → `pseudoregalia\Content\Paks\` |
| **2** | Cole `pseudoregalia-PTBR_P.pak` nessa pasta |
| **3** | Jogue! |

**Para desinstalar:** delete o arquivo `pseudoregalia-PTBR_P.pak`. O jogo volta ao inglês automaticamente.

---

## <img src="assets/icons/info.svg" width="22" height="22" alt="IA"> Tradução por IA — Pode Haver Erros

Esta tradução foi gerada por um **modelo de linguagem local** e **não foi revisada por um tradutor humano profissional**. Isso significa que:

- Algumas frases podem soar **estranhas ou literais demais**
- Termos de gameplay e habilidades foram **mantidos em inglês** intencionalmente (Dream Breaker, Sun Greaves, Cling Gem, etc.)
- Nomes próprios (Sybil, Princess) também **não foram traduzidos**
- Pode haver ocasionalmente **erros de contexto ou de género gramatical**

Se encontrar algum erro, **toda ajuda é bem-vinda!**

---

## <img src="assets/icons/help-circle.svg" width="22" height="22" alt="Reportar"> Reportar Erros e Bugs

Encontrou uma tradução estranha, texto em inglês que deveria estar traduzido, ou qualquer outro problema?

**Por favor, abra uma [Issue](../../issues) neste repositório** com:

1. O **local** onde encontrou o erro (menu, NPC, zona do mapa, etc.)
2. O **texto original** (em inglês, se lembrar)
3. O **texto traduzido** que apareceu
4. Uma **sugestão de correção** (opcional, mas muito útil!)

Quanto mais detalhes, mais fácil é corrigir. Obrigado pela ajuda!

---

## <img src="assets/icons/help-circle.svg" width="22" height="22" alt="FAQ"> FAQ

**O jogo continua em inglês após instalar o .pak!**
Verifique se o arquivo está na pasta correta: `pseudoregalia\Content\Paks\` e se o nome termina em `_P.pak`. Confirme também que o jogo foi fechado e reaberto após copiar o arquivo.

**Os textos aparecem com letras estranhas ou quadradinhos!**
Isso não deve acontecer com esta versão. Se ocorrer, reporte como uma Issue.

**O jogo travou ou crashou após instalar!**
Delete o arquivo `pseudoregalia-PTBR_P.pak` para voltar ao inglês. Reporte o crash como uma Issue com o máximo de detalhes que puder.

**Por que não tem acentos?**
O jogo usa uma fonte customizada ASCII-only. Adicionar acentos causa crash no jogo. Veja a seção [Limitação](#-limitação-sem-acentos) acima.

**Como desfaço a tradução?**
Delete `pseudoregalia-PTBR_P.pak` da pasta `Paks\`. O jogo volta ao inglês automaticamente, sem precisar de reinstalação.

---

## <img src="assets/icons/file-text.svg" width="22" height="22" alt="Licença"> Aviso Legal

Este é um projeto **não-oficial** feito por fãs, sem afiliação com **rittzler** (desenvolvedor do jogo). **Pseudoregalia** e todos os seus conteúdos são propriedade de seus respectivos criadores. Este projeto não distribui nenhum arquivo do jogo original.

---

## <img src="assets/icons/heart.svg" width="22" height="22" alt="Créditos"> Créditos

- **Tradução**: [NetoTTT](https://github.com/NetoTTT) (com auxílio de IA)
- **Jogo Original**: [rittzler](https://store.steampowered.com/app/2365810/Pseudoregalia/) — obrigado pelo jogo incrível!
- **Ferramentas**: [UAssetAPI](https://github.com/atenfyr/UAssetAPI) · [repak](https://github.com/trumank/repak)
- **Código-fonte da pipeline de tradução**: [ue5-pak-translator](https://github.com/NetoTTT/ue5-pak-translator)
