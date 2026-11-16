# Rurouni Kenshin: Enjou! Kyoto Rinne (PS2) - Patch de Tradução PT-BR

Projeto de tradução independente para o jogo **Rurouni Kenshin: Enjou! Kyoto Rinne** (PlayStation 2, SLPS-25685, NTSC-J) para Português do Brasil.

O patch funciona em emulador (PCSX2) e em PlayStation 2 real via OPL. **Se for jogar no console, leia antes a seção "Problema conhecido" mais abaixo.**

## 🐞 Link Discord para relatar bugs : https://discord.com/invite/mTuNMPw

---

## 📊 Status da Tradução — Versão 1.0

A v1.0 é a primeira versão completa da tradução. Ela é recente e **não foi jogada de ponta a ponta em console depois das últimas revisões**, então relate qualquer problema (veja "Relatar problemas").

| Categoria | Status | Observação |
| :--- | :--- | :--- |
| **Menus e Interface** | ✅ Traduzido | Opções, atributos, confirmações, habilidades e locais |
| **Itens** | ✅ Traduzido | Nomes e descrições (nomes abreviados para caber nas caixas) |
| **História e Eventos** | ✅ Traduzido | Diálogos, narração, nomes, cenas e créditos, com texto revisado de ponta a ponta |
| **Tutoriais e Mensagens de Sistema** | ✅ Traduzido | Inclui as mensagens de Memory Card |
| **Texturas de Interface** | ✅ Traduzido | Menus, tela de duelo, títulos, tela de carregamento, atributos e modo extra do Inuyasha |
| **Fonte** | ✅ Completa | Alfabeto latino com acentos e cedilha |
| **Áudio / Dublagem** | ❌ Original | Vozes em japonês |

### O que continua em japonês (de propósito ou por limitação)

* Áudio e vozes.
* Nomes dos golpes (kanji nas texturas de habilidade) e fachadas de lojas/cenário, mantidos como no original.
* Os botões L1/R1/R2/R3 aparecem como letras no texto (o jogo japonês também os escreve assim); ○ □ △ X e a cruz direcional usam os ícones do jogo.
* Algumas texturas isoladas ou textos muito raros podem ter escapado. Se achar algum, avise.

*Parte do texto foi traduzida com auxílio de inteligência artificial e depois revisada; ainda podem ocorrer erros de revisão ou formatação.*

---

## 📦 Arquivos do Patch (v1.0)

| Arquivo | Uso | Aplica sobre |
| :--- | :--- | :--- |
| `Kenshin_PTBR_v1.0_traducao.xdelta` | **Obrigatório.** A tradução completa | ISO **original japonesa** |
| `Kenshin_PTBR_v1.0_480p.xdelta` | Opcional. Vídeo em 480p (varredura progressiva) | ISO **já traduzida** |
| `Kenshin_PTBR_v1.0_widescreen.xdelta` | Opcional. Câmera 3D em 16:9 | ISO **já traduzida** |
| `Kenshin_PTBR_v1.0_480p_videos.xdelta` | Opcional (experimental). Vídeos também em 480p; use **junto com** o 480p | ISO **já traduzida** |
| `LEIA-ME.txt` | Instruções completas | — |

---

## 🛠️ Como Aplicar o Patch

### Requisitos Prévios
* **ISO Original Japonesa (SLPS-25685)** sem nenhuma modificação.
  * **MD5:** `57A0D3E58B44865812522C3AD21130A9`
* Um aplicador de patch como o **DeltaPatcher** (GUI) ou o **xdelta3** (linha de comando).

### Passo a Passo pelo DeltaPatcher (Interface Gráfica)

1. Abra o **DeltaPatcher** (incluso no pacote em `Ferramentas\DeltaPatcher\DeltaPatcher.exe`, ou use a versão de sua preferência).
2. No campo **Original file**, selecione a sua ISO original japonesa.
3. No campo **XDelta patch**, selecione `Kenshin_PTBR_v1.0_traducao.xdelta`.
4. Escolha o nome da ISO de saída e clique em **Apply patch**.
5. Confira o resultado:
   * **Tamanho:** `1.638.363.136 bytes`
   * **SHA-256:** `D190E355844A2F22F3C0C768F5C57182B2551855ABDEF6E57124A6B35D948079`
6. *(Opcional)* Para cada patch opcional que quiser, repita o processo usando como **Original file** a **ISO já traduzida** (ou o resultado de outro patch opcional), o `.xdelta` opcional como patch e **outro nome** para a ISO de saída. Pode usar um, dois ou os três, em qualquer ordem. O tamanho final é sempre `1.638.363.136 bytes`.

<details>
<summary><b>SHA-256 esperado para cada combinação</b></summary>

| Combinação | SHA-256 |
| :--- | :--- |
| Só tradução | `D190E355844A2F22F3C0C768F5C57182B2551855ABDEF6E57124A6B35D948079` |
| Tradução + 480p | `351CE36FA719B4B6BCC5A4676AA36466F37949F5AA0225EBC74C2A6CFBD40D96` |
| Tradução + widescreen | `0D77A6BEF2BBFD2191524D45A690539ABD7FBB99243D33B928C72C7B3351E4B7` |
| Tradução + vídeos 480p (só) | `D725A786258A070A02A69E817F5DA7145A2FE8D99E4744EC4817F1545187305F` |
| Tradução + 480p + widescreen | `9EB82198A14596967F0436A4C0C49AD22A6929472A2EBED36218BF1A895C4DF6` |
| Tradução + 480p + vídeos 480p | `DF2B813DB7DDC5AEFBBFAA765A94EFA74BA4D228567D8126C0D8FCB054C271B8` |
| Tradução + widescreen + vídeos 480p | `2280A37F3C93F4E128095E415082BE3D8F5FE8BA81E71EF792C60B509BA163B4` |
| Tradução + 480p + widescreen + vídeos 480p | `71EBE9CDBC5651691FDC9458B8172DFCEE644D88632AF509565460D6A4EBF9C6` |

Se o resultado não tiver o SHA-256 esperado, algum passo foi aplicado sobre a ISO errada.

</details>

<details>
<summary><b>SHA-256 dos arquivos .xdelta (para conferir o download)</b></summary>

| Arquivo | SHA-256 |
| :--- | :--- |
| `Kenshin_PTBR_v1.0_traducao.xdelta` | `821164BC42DD4B0A044F7E910CC0DE813595918915DE4101C44D30CCDA6230C2` |
| `Kenshin_PTBR_v1.0_480p.xdelta` | `8B73BBD907034FFD4EF03FC0E61AFE4D00F242357F50B3E870478F265455E8C2` |
| `Kenshin_PTBR_v1.0_widescreen.xdelta` | `1C8B33FA8B55B34485E1CD1A1139C86666A05F75146F7EE99B3D63C3E89FCFD8` |
| `Kenshin_PTBR_v1.0_480p_videos.xdelta` | `B48E0ED33148ADE5C6EEBB83D13EEFE2840A2B1951A8E38FB10DF1A5A6387B0F` |

</details>

### Linha de Comando (xdelta 3.1.0)

```bash
xdelta-3.1.0-x86_64.exe -d -s "original.iso" Kenshin_PTBR_v1.0_traducao.xdelta "traduzida.iso"
xdelta-3.1.0-x86_64.exe -d -s "traduzida.iso" Kenshin_PTBR_v1.0_480p.xdelta "traduzida_480p.iso"
xdelta-3.1.0-x86_64.exe -d -s "traduzida_480p.iso" Kenshin_PTBR_v1.0_widescreen.xdelta "traduzida_480p_wide.iso"
xdelta-3.1.0-x86_64.exe -d -s "traduzida_480p_wide.iso" Kenshin_PTBR_v1.0_480p_videos.xdelta "traduzida_completa.iso"
```

Os patches opcionais são gerados **sem checksum de propósito** (opção `-n` do xdelta), para que um possa ser aplicado sobre o resultado do outro. Por isso eles só valem para a tradução da **mesma versão** (v1.0).

---

## 🎛️ Sobre os Patches Opcionais

* **480p (varredura progressiva)** — *testado no emulador e no PS2.*
  O jogo passa a enviar vídeo 480p em vez de 480i. A imagem continua 640x448, centralizada na tela de 480 linhas (faixas pretas finas em cima e embaixo). Requer cabo **componente (YPbPr)** e TV que aceite 480p; no menu do PS2, deixe a saída de vídeo em "Y Cb/Pb Cr/Pr". Com cabo composite, S-Video ou SCART-RGB o 480p **não exibe imagem**: nesse caso, não aplique este patch.
* **Widescreen 16:9** — *testado no emulador e no PS2.*
  Alarga o campo de visão da câmera 3D em 4/3. O console continua enviando imagem 4:3 e a TV a estica, então coloque a TV no modo 16:9 / Wide / Esticar. Interface (HUD), menus, textos, imagens estáticas de cutscene e vídeos são 2D em 4:3 e aparecem esticados na horizontal. Funciona com ou sem o 480p. Sem modo 16:9 na TV, não aplique.
* **Vídeos em 480p (experimental)** — *testado no PS2.*
  Os 2 vídeos do jogo passam a sair em 480p, sem trocar de modo no início e no fim. A imagem não fica mais nítida (o ganho é só não trocar de modo), e a tela ainda pisca por um instante ao entrar e ao sair do vídeo. Aplique **somente junto com o 480p**. Se a abertura travar, ficar com tela preta ou distorcida, não use este patch (os outros funcionam sem ele).

---

## ⚠️ Problema Conhecido: travamentos no PS2 real (OPL)

Em testes em **PS2 real (FAT, SCPH-30001) com OPL**, com a ISO no **HD interno** e no **pendrive USB**, a tela de carregamento às vezes fica "eterna" (o jogo trava) e, mais raramente, o jogo nem inicia (tela preta).

**Isso também acontece com a ISO japonesa original, sem nenhum patch.** Nos testes feitos com a ISO original:

| Mídia | Passou | Travou | Tela preta |
| :--- | :---: | :---: | :---: |
| HD interno | 1 | 6 | 2 |
| USB | 6 | 5 | 0 |
| **Total** | **7** | **11** | **2** |

As ISOs traduzidas travaram em 8 de 23 tentativas. As mídias usadas nos testes foram diferentes, então os números não são diretamente comparáveis, mas **não há indício de que a tradução piore o problema**, e a tradução não é a causa. Todos esses testes foram feitos sem os patches opcionais. A cena em que o problema foi percebido (aparecimento do Shishio) carrega normalmente no emulador.

**Se acontecer com você:**
* Reinicie o console e tente de novo; a trava é intermitente.
* Possíveis contornos (**não verificados**): outro pendrive ou porta USB, ISO sem fragmentação, outra versão do OPL e os modos de compatibilidade do OPL para este jogo.
* Uma build anterior (v57), com 480p e widescreen, foi jogada por mais de 3 horas em PS2 real sem travar. Se o modo de vídeo influencia, ainda não sabemos (hipótese não testada).

---

## 🐞 Relatar Problemas

Se encontrar texto cortado, caractere estranho, tela travada ou trecho ainda em japonês, anote:
* onde estava (capítulo/tela) e o que aparecia (print ou foto, se possível);
* em qual plataforma jogou (PCSX2 ou PS2 real, e como: OPL por USB/HD, disco etc.);
* qual combinação de patches usou e o **SHA-256 da sua ISO**.

Isso permite corrigir rápido nas próximas versões.

---

## 📝 Histórico

* **v1.0** — Texturas "N Luta" (tela de duelo e de carregamento) e todas as texturas do modo extra do Inuyasha traduzidas. Texto da história revisado por completo (nomes, termos e tom padronizados; ~2.500 textos ajustados), nomes de itens abreviados para caber nas caixas, ajustes nas telas de atributos, habilidades e tutoriais, rótulo do duelo reposicionado. Patch de vídeos em 480p (experimental, validado no PS2).
* **v57** — Build testada por mais de 3 horas em PS2 real (com 480p e widescreen), sem travamentos.

---

## 📢 Canais e Comunidade

Acompanhe o desenvolvimento do projeto, assista a testes de gameplay e ajude a reportar erros!

* 📺 **Canal de Projetos (GScNine):** [youtube.com/@gscnine](https://www.youtube.com/@gscnine) — *Vídeos de mods, tradução, eletrônica e hardware.*
* 🎮 **Canal de Gameplay (GScNine Play):** [youtube.com/@gscnineplay](https://www.youtube.com/@gscnineplay) — *Gameplays e testes de jogos.*
* 💬 **Discord:** Entre no nosso servidor [https://discord.com/invite/mTuNMPw](https://discord.com/invite/mTuNMPw) — *Relatar bugs e acompanhar novos projetos.*

---

## ⚖️ Avisos Legais e Créditos

* Os patches disponibilizados **não contêm nenhum arquivo protegido por direitos autorais** da ISO original além das partes alteradas (textos, fonte, texturas, tabela de itens e algumas instruções do executável). **Não distribua a ISO do jogo**; distribua somente os arquivos `.xdelta`.
* Fonte dos glifos latinos: *Open Sans (Bold)*, criada por *Steve Matteson* e disponibilizada sob a licença [SIL Open Font License (OFL)](https://openfontlicense.org)
* Fontes adicionais para texturas e efeitos:  *A Ai Love*, criada por [Wahyu Eka Prasetya (wepfont)](https://wepfont.com/) e disponibilizada gratuitamente.
* * Fontes adicionais para texturas e efeitos : **Shodo** (`Shodo_font190430`), criada por **Yasuaki Yasumelt** e disponibilizada sob licença aberta.
* Rurouni Kenshin e seus personagens pertencem aos respectivos detentores dos direitos. Projeto de fã, sem fins lucrativos.
