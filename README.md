# Rurouni Kenshin: Enjou! Kyoto Rinne (PS2) - Patch de Tradução PT-BR

Projeto de tradução independente para o jogo **Rurouni Kenshin: Enjou! Kyoto Rinne** (PlayStation 2) para Português do Brasil (PT-BR). 

O foco principal deste projeto é garantir total compatibilidade e funcionamento perfeito no **hardware original (PlayStation 2 Fat / Slim)** via OPL, além de emuladores (PCSX2).

Essa e outras traduções são feitas com assistência de IA.

---

## 📊 Status da Tradução (Versão Preliminar)

A tradução está em fase de testes e revisão. Boa parte do texto foi traduzida com o auxílio de inteligência artificial, portanto **podem ocorrer erros de revisão ou formatação**.

| Categoria | Progresso | Observação |
| :--- | :--- | :--- |
| **Menus e Interface** | 100% | Opções, distribuição de pontos, confirmações, golpes e locais |
| **Itens** | 100% | Nomes e descrições dos itens |
| **História e Eventos** | ~19% | Diálogos e narração em andamento |
| – *Diálogos Longos* | ~16% | 1.124 de 8.105 textos distintos |
| – *Nomes e Rótulos Curtos* | ~70% | Personagens, lugares e títulos |
| **Texto Total (Geral)** | ~21% | 1.982 de 9.435 textos distintos |
| **Imagens (Títulos/Botões)** | 0% | Pendente |
| **Áudio / Dublagem** | 0% | Áudio original mantido |

*Nota: Textos e imagens ainda não traduzidos continuarão sendo exibidos em japonês.*

---

## 🛠️ Como Aplicar o Patch

### Requisitos Prévios
* **ISO Original Japonesa (SLPS-25685)** sem nenhuma modificação.
  * **MD5:** `57A0D3E58B44865812522C3AD21130A9`
* O arquivo de patch (`.xdelta`).
* Um aplicador de patch como o **DeltaPatcher** (GUI) ou **xdelta3**.

---

### Passo a Passo pelo DeltaPatcher (Interface Gráfica)

1. Baixe e abra o **DeltaPatcher** (localizado em `Ferramentas\DeltaPatcher\DeltaPatcher.exe` ou utilize a versão de sua preferência).
2. No campo **Original file**, selecione a sua ISO original japonesa do jogo (`SLPS-25685`).
3. No campo **XDelta patch**, selecione o arquivo do patch (ex: `Kenshin_PTBR_v7.xdelta`).
4. Clique em **Apply patch**.

Ao finalizar, o arquivo de saída gerado deverá ter:
* **Tamanho aproximado:** `1.636.470.784 bytes` (~1,6 GB)
* **SHA-256:** `B721AA34757C96AB62605BB726E116DC8C1C0CCE48186AE13840B8DC96E9C2A9`

---

### Linha de Comando (xdelta 3.1.0)

Caso prefira utilizar o prompt de comando ou terminal:

```bash
xdelta-3.1.0-x86_64.exe -d -s "original.iso" Kenshin_PTBR_v7.xdelta "traduzida.iso"
```

---

## 📢 Canais e Comunidade

Acompanhe o desenvolvimento do projeto, assista a testes de gameplay e ajude a reportar erros!

* 📺 **Canal de Projetos (GScNine):** [youtube.com/@gscnine](https://www.youtube.com/@gscnine) — *Vídeos de mods, tradução, eletrônica e hardware.*
* 🎮 **Canal de Gameplay (GScNine Play):** [youtube.com/@gscnineplay](https://www.youtube.com/@gscnineplay) — *Gameplays e testes de jogos.*
* 💬 **Discord:** Entre no nosso servidor ([https://discord.com/invite/mTuNMPw](https://discord.com/invite/mTuNMPw))) para reportar bugs e sugerir correções de texto!

---

## ⚖️ Avisos Legais e Créditos

* O patch disponibilizado **não contém nenhum arquivo protegido por direitos autorais** da ROM/ISO original. Ele contém apenas os dados modificados de tradução (textos, fontes e tabela de itens).
* Fonte dos glifos latinos: *Open Sans Bold* (SIL OFL 1.1).
