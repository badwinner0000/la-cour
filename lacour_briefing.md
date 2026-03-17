# LA COUR — Briefing Completo do Projeto

## IDENTIDADE

- **Nome do RPG:** La Cour
- **Ambientação:** Paris, 2025. RPG de vampiros focado em narrativa e política
- **Tom:** Gótico aristocrático, elegante, tenso. Sem linguagem de "jogo" nos textos públicos. Sem mencionar "one shot"
- **Idioma:** Português brasileiro, com termos em francês para elementos canônicos

---

## PALETA DE CORES

| Variável | Hex | Uso |
|---|---|---|
| `--blk` | `#070202` | Fundo principal |
| `--drk` | `#110404` | Painéis escuros |
| `--drk2` | `#1b0606` | Cards, blocos secundários |
| `--red` | `#8b1a1a` | Cor de destaque principal |
| `--red2` | `#6b1010` | Bordas, detalhes vermelhos |
| `--gld` | `#c9a97a` | Dourado (ênfase, quotes) |
| `--crm` | `#f4ede0` | Creme (painéis claros) |
| `--crm2` | `#ece4d4` | Creme escuro (cards claros) |
| `--txt` | `#1c0a0a` | Texto sobre fundo creme |
| `--mut` | `#5c3030` | Texto muted sobre creme |

**Versão Yoble (sem CSS variables):**
- Fundo escuro: `#0d0303` / `#1a0505`
- Vermelho principal: `#7a1010` / `#8b1a1a`
- Dourado/creme: `#c8a888` / `#f5f0e8`
- Bordas: `#2e0808` / `#3a0808`

---

## TIPOGRAFIA

**Site (Google Fonts):**
- Títulos: **Playfair Display** (weights: 400, 700, 900, italic)
- Corpo: **Cormorant Garamond** (weights: 300, 400, 600, italic)
- Labels/UI: **Montserrat** (weights: 300, 400, 500)

**Yoble (fontes do sistema):**
- Títulos: `'Palatino Linotype'`
- Corpo: `'Verdana'`
- Labels/UI: `'Segoe UI'`

---

## LORE CANÔNICO

### Le Premier
- Consciência anterior ao conceito de vampiro — emergiu quando a morte encontrou a vontade de recusar
- ~8.000 anos, sem forma física estável
- Não criou vampiros por projeto — infectou por curiosidade
- Em 1698 Jean-Baptiste Moreau o contatou e ofereceu seu corpo para acabar com o colapso vampírico de Paris
- Le Premier habitou Moreau e em três noites destruiu todos os clãs que não assinaram o Pacto — a carnificina foi o que forçou a assinatura
- Os cinco clãs atuais são os que sobreviveram porque assinaram a tempo
- Moreau traiu Le Premier antes do prazo com ajuda de L'Ancienne e escapou — Le Premier foi expulso do corpo mas não destruído
- O Pacto expirou em 1938. Levou 87 anos para Le Premier recuperar força suficiente para agir
- Usa Les Dévoreurs como instrumentos via *La Voix Ancienne* — eles não sabem
- Está rastreando Touchés de linhagem antiga para usá-los como âncoras

### L'Ancienne
- Ser muito antigo, contemporâneo de Le Premier
- Integrado em Paris como vampiro comum, membro de um clã, com identidade fabricada
- Ajudou Moreau a escapar em 1698 por razões próprias que nunca revelou
- Os arquivos da Corte de 1698 têm páginas rasuradas, trechos arrancados, parágrafos queimados
- Uma frase resta: *"Elle était là avant nous."*
- Pode ser lenda. Pode não ser. Ninguém sabe quem rasurouos arquivos.

### La Cour
- Fundada em 1698 por **Jean-Baptiste Moreau** (*Le Compositeur*)
- Local: câmara subterrânea sob o que viria a ser o Palais Garnier
- O Pacto foi assinado no medo, não por consenso — os que se opuseram foram destruídos
- Le Compositeur desapareceu décadas depois — na verdade virou **Séraphin**
- Séraphin = Moreau. Identidade completamente reconstruída ao longo de décadas

### As Três Leis
1. Nenhum Eterno revelará nossa natureza ao mundo mortal
2. Nenhum Eterno criará descendentes sem sanção da Corte
3. O Sangue de um Pacto é sagrado — trair é a única morte verdadeira

### L'Embrassement (O Abraço)
- Dois estágios: morte clínica completa + reanimação pelo Sangue Eterno
- Dura 12–24h, irreversível
- Coração para, memória torna-se permanente e acumulativa
- Envelhecimento cessa no momento exato do Abraço
- Sensibilidade solar proporcional à linhagem

---

## OS CINCO CLÃS

### Clã Néant — Mental · Psíquico
**Líder:** Isabeau du Néant — *La Dame* — 547 anos — abraçada ~1478 — aparência 25 anos
**Cobertura atual:** Conselheira espiritual/confessora em Paris
**Poderes:** Leitura mental, sugestão, apagamento de memória, plantio de pensamentos, Ligação (fio entre duas mentes), Espelho (pessoa vê seus próprios pensamentos como externos)
**Dificuldades:** Fácil (sentir emoções, detectar mentiras, criar confiança), Médio (leitura superficial, sugestão simples, apagar memória recente, Ligação), Difícil (memórias profundas, crenças complexas, compulsão longa, Espelho), Muito difícil (sonhos, quebrar mentes, ler mentes resistentes)
**Fraqueza:** Dissolução progressiva do ego com o uso — Estável → Permeável → Poroso → Dissolvido → Vazio
**Em Paris:** 21 confirmados + 4 Errantes conhecidos

### Clã Beaumont — Social · Manipulação
**Líder:** Rémi Baumont — *Le Prince* — 320 anos — abraçado ~1705 — aparência 36 anos
**Cobertura atual:** Playboy herdeiro, anfitrião social
**Poderes:** Compulsão vocal, aura de confiança, charme prolongado, Detecção de mentiras (tom e microexpressões), Apagamento pós-manipulação, Multidão (mover grupos emocionalmente)
**Dificuldades:** Fácil (impressão de confiança, ler hierarquia social), Médio (compulsão vocal, aura prolongada, dependência gradual, Detecção), Difícil (charme por dias, apagamento pós-manipulação, lealdade fabricada, Multidão), Muito difícil (dependência permanente, agir contra interesse próprio, operar grupo inteiro)
**Fraqueza:** Deterioração por isolamento — Conectado → Isolado → Privado → Faminto → Colapsado
**Em Paris:** 18 confirmados + 6-7 Errantes

### Clã Braise — Físico · Combate
**Líder:** Viktor Gregorovitch — *La Bête* — 139 anos — abraçado ~1886 — aparência 40 anos
**Cobertura atual:** Dono de bar no 11º arrondissement / executor informal da Corte
**Poderes:** Força amplificada, absorção de impacto, regeneração, resistência a fogo/frio/veneno, Absorção (redistribuir impacto), Presença intimidadora (paralisia breve)
**Dificuldades:** Fácil (força básica, absorver impacto, sentir perigo), Médio (força sustentada, regeneração menor, resistência extrema, Absorção), Difícil (regeneração severa, força destrutiva, Presença), Muito difícil (regeneração permanente, força máxima sustentada)
**Fraqueza:** Desregulação física progressiva — Calibrado → Tenso → Desregulado → Incontido → Frenesi
**Em Paris:** 28 confirmados + 5 Errantes (monitorados ativamente)
**Nota:** Viktor não foi o líder original. Assumiu em 1962 após La Société Solaire eliminar o líder anterior.

### Clã Voile — Sombra · Ilusão
**Líder:** Marguerite Voile — *La Voix* — 230 anos — abraçada ~1795 — aparência 30 anos
**Cobertura atual:** Cantora de jazz em clube noturno no 6º arrondissement
**História:** Era cantora, foi abraçada pelo fundador do clã Étienne Voile como esposa de conveniência. O fundador e as outras esposas foram morrendo misteriosamente. Marguerite foi a única a sobreviver e assumiu o clã.
**Poderes:** Camuflagem, ilusão localizada, manipulação de luz, movimento silencioso, Projeção (ilusões de pessoas/objetos), Máscara (assumir aparência de outra pessoa)
**Dificuldades:** Fácil (suprimir presença, manipular luz, movimento silencioso), Médio (camuflagem completa, ilusão simples, Projeção), Difícil (ilusão sustentada, apagar presença da memória, Máscara), Muito difícil (ilusão de ambiente inteiro, identidade falsa por dias)
**Fraqueza:** Compulsão pela invisibilidade — Estável → Habituado → Compulsivo → Instintivo → Dissolvido
**Em Paris:** 15 confirmados + 3 Errantes

### Clã Ténèbre — Sangue · Cura
**Líder:** Theodore Harlow — *Le Docteur* — 168 anos — abraçado ~1857 — aparência 52 anos
**Cobertura atual:** Pesquisador independente sem vínculo institucional
**História:** Americano, cirurgião, chegou a Paris nos anos 1850 para estudar medicina europeia. Descobriu os vampiros por investigação científica e pediu o Abraço ele mesmo após três anos de pesquisa. Assumiu a liderança do grupo décadas depois.
**Origem do clã:** O Ténèbre não tinha fundador único — era um grupo que sobreviveu à carnificina de 1698 e assinou o Pacto coletivamente.
**Poderes:** Sentido de sangue, cura, elo sanguíneo, coagulação, Dependência (sangue preparado para criar vínculo), Veneno (envenenar o próprio sangue), Aceleração/detenção de cura, Detecção de Grande Fadiga
**Dificuldades:** Fácil (sentir sangue, saúde, detectar Fadiga), Médio (curar ferimentos menores, elo sanguíneo, coagulação, Dependência básica, Veneno básico), Difícil (acelerar/deter cura alheia, sentir fraquezas específicas, rastrear rastro sanguíneo, Dependência intensa), Muito difícil (curar ferimentos permanentes, dependência irreversível, veneno letal)
**Fraqueza:** Fome amplificada — alimenta-se o dobro. Saciado → Com fome → Faminto → Desesperado → Frenesi de Fome
**Em Paris:** 15 confirmados + 2-3 sem rastro

---

## HIERARQUIA

| Posto | Idade | Descrição |
|---|---|---|
| **L'Éternité** | 130+ anos | Conselho Supremo. Os cinco líderes de clã |
| **Les Établis** | 50–130 anos | Classe política real da Corte |
| **Les Récents** | 15–50 anos | Operacionais e executores |
| **Les Nouveau-Nés** | < 15 anos | Sem direitos políticos, sob tutela do criador |

---

## O CONSELHO (L'ÉTERNITÉ)

| Personagem | Clã | Idade | Alcunha | Aparência |
|---|---|---|---|---|
| **Isabeau du Néant** | Néant | 547 anos | La Dame | 25 anos |
| **Rémi Baumont** | Beaumont | 320 anos | Le Prince | 36 anos |
| **Viktor Gregorovitch** | Braise | 139 anos | La Bête | 40 anos |
| **Marguerite Voile** | Voile | 230 anos | La Voix | 30 anos |
| **Theodore Harlow** | Ténèbre | 168 anos | Le Docteur | 52 anos |

---

## NPCS E AMEAÇAS

**Séraphin** — É Jean-Baptiste Moreau (Le Compositeur). Abraçou os jogadores. Sabe mais do que qualquer outro ser vivo sobre Le Premier e o Pacto de 1698.

**Les Dévoreurs** — Liderados por Armand Voss (expulso em 1998). Instrumentos inconscientes de Le Premier via *La Voix Ancienne*.

**La Société Solaire** — Fundada 1887. Liderada por Madame Leclair (identidade desconhecida). Eliminaram 8 Eternos em 10 anos. Têm informante dentro da Corte.

**L'Oubli** — Vampiros em Grande Fadiga. Instinto puro. Eliminação imediata é política oficial. Viktor lidera as equipes desde 1980.

**L'Ancienne** — Ser muito antigo integrado em Paris. Arquivos rasurados. Pode ser lenda.

---

## LES TOUCHÉS (OS TOCADOS)

Descendentes humanos de relações entre vampiros e humanos. Não abraçados — produto de paixão ou descuido ao longo de séculos. Indiferente ao Pacto — vampiros imortais se apaixonam.

**Status:** Proibidos pela Corte. Existir como Touché é evidência de violação das Três Leis.
**Manifestação:** Imprevisível — pode saltar gerações.
**Traços:** Atração involuntária de vampiros, instinto aguçado, sonhos/visões de memórias da linhagem, resistência à compulsão, cicatrização acelerada.
**Por que são caçados:** Dévoreurs os eliminam por crença. Société Solaire os recruta ou elimina. Le Premier rastreia os de linhagem mais antiga como possíveis âncoras.

---

## LES ERRANTS (OS ERRANTES)

Vampiros fora da estrutura da Corte — expulsos ou por escolha. Mantêm poderes do clã e obrigação das Três Leis. Perdem acesso ao Arquivo, proteção institucional e credibilidade. A Corte os monitora como ameaça.

---

## O MOMENTO ATUAL (SEM SPOILERS)

- Pacto expirado há 87 anos. Le Premier ficou décadas recuperando força.
- Rachadura no Conselho: Viktor x Rémi em impasse
- Isabeau ficou 3 noites isolada — nunca aconteceu em 200 anos
- Ataques dos Dévoreurs aumentaram 40% em 6 meses, mais cirúrgicos
- Société Solaire eliminou 2 Établis em 3 meses
- Rumor: informante dentro da Corte
- Rumor: Nouveau-Né entrou em Grande Fadiga com apenas 4 anos
- Rumor: alguém adicionou documento ao Arquivo de 1698
- Séraphin convocou os personagens para reunião no 8º arrondissement

---

## O SISTEMA

**6 Atributos (1–5):** SOC, EGO, SIG, FIS, VEL, HP (30 + FIS×5)
**Criação:** 15 pontos distribuídos, máximo 4 em qualquer atributo
**Rolagem:** dados = atributo relevante. Sucesso em 4, 5 ou 6.
- 0 sucessos: falha + complicação
- 1–2: funciona com custo
- 3+: sucesso limpo. 5+: vantagem adicional

**Dificuldades dos poderes:** Fácil / Médio / Difícil / Muito difícil — narrador calibra com base no personagem e contexto.

**Consequências:** Frenesi (HP < 10), Exposição (3 fichas = Société), Dívida de Sangue, Sinal da Fadiga (deterioração de EGO)

---

## SITE (GITHUB PAGES)

**URL:** `https://badwinner0000.github.io/la-cour/`

**Arquivos:**
- `index.html` — Página inicial
- `historia.html` — Lore completo
- `personagens.html` — Grid de personagens
- `perfil.html` — Ficha individual (template)
- `momento-atual.html` — Clima atual
- `sistema.html` — Regras
- `briefing-jogador.html` — Resumo para jogadores

**Para adicionar personagem:** duplicar `perfil.html`, renomear para `perfil-nomepersonagem.html`, editar dados, fazer upload no GitHub, linkar no `personagens.html`.

---

## YOBLE — RESTRIÇÕES CONFIRMADAS

❌ NÃO funciona: `<style>` tags, `background-size`, `display:inline-block`, `position:absolute` em posts

✅ FUNCIONA: `onmouseover`/`onmouseout` inline JS, `background-image: url()`, `background-repeat`, `background-position`, `position:absolute` em guias, classes UIkit, layout full-bleed `width:1365px; margin-left:-420px;`, `display:block`

---

## ARQUIVOS YOBLE CANÔNICOS

| Arquivo | Descrição |
|---|---|
| `yoble_nav.html` | Card de navegação com logo, links e botões Fórum/Entrar/Sair |
| `yoble_guia.html` | Guia do universo: header hover dropdown 4 colunas, fundo creme |
| `yoble_turno_jogador.html` | Turno de jogador: header escuro, corpo creme, stats hover |
| `yoble_turno.html` | Turno do narrador |
| `yoble_post.html` | Post de admin |

**Logo:** `https://64.media.tumblr.com/8957f7314f33baca95953b37ac967eea/8b8ece2738375144-63/s250x400/f0f9d3d405de1a87187f45a57aeb7f98811e25f2.png`

**Links da comunidade (ID 307424):**
- Fórum: `/Main/communities/forum/307424`
- Entrar: `/Main/communities/add-member/307424`
- Sair: `/Main/communities/out-member/307424`

---

## DOCUMENTOS WORD

- `LaCour_Mestre_v7.docx` — Escudo do mestre com todos os segredos
- `LaCour_Jogadores_v7.docx` — Guia do jogador sem spoilers
