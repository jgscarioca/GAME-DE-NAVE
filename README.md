# 🌕 CYBER CORE: LUNAR BASE TOWER DEFENSE

Um jogo de **Tower Defense Cartoonesco** desenvolvido em **HTML5 Canvas**, **Vanilla CSS** e **Web Audio API**, ambientado na base lunar conceitual oficial.

Defenda o **Airlock do Núcleo Lunar** contra 20 ondas de robôs invasores gerenciando **Energia** (construção e upgrades) e **Mana** (habilidades ativas e pesquisas no Laboratório)!

---

## 🗺️ Mapa Lunar Oficial & Estrutura

- **Fundo Gráfico Oficial da Base Lunar**: Mapa widescreen `1024 x 576` com crateras, domos de pesquisa, painéis solares, usinas extratoras de He3 e Terra visível no horizonte.
- **Esteira S-Curve dos Robôs**:
  - Partida na **START ZONE** (esquerda).
  - Percorre a esteira através dos três segmentos táticos com curvas suaves e linha neon pulsante.
  - Destino final no **AIRLOCK TO CORE** (direita).
- **Locação das Máquinas (Build Slots)**:
  - Pedestal de 4 pilares na largada.
  - Plataforma octagonal e gerador cilíndrico na curva inferior.
  - Hexágono de alta prioridade marcado como **CRITICAL BUILD SLOT**.
  - 5 slots centrais amplos nas **BUILD ZONES**.
  - Bases táticas no interior dos arcos da esteira e junto aos extratores.

---

## ⚡ Sistema Duplo de Recursos: Energia & Mana

| Recurso | Utilidade | Como Gerar |
| :--- | :--- | :--- |
| **⚡ ENERGIA** | Construção de novas torres, evolução para os Níveis 1 a 3 e especializações (Nível 4). | Abate de inimigos + bônus de término de onda + Reator Auxiliar. |
| **💠 MANA** | Disparo das Habilidades Táticas Ativas do Comandante (<kbd>Q</kbd>, <kbd>W</kbd>, <kbd>E</kbd>) + Pesquisas no Laboratório. | Regeneração passiva constante (`+2.5 Mana/s`) + Orbes de Mana de mechas blindados e Titãs. |

---

## 🚀 Habilidades Táticas do Comandante

- <kbd>Q</kbd> **Pulso PEM Orbital** (Custo: `30💠 Mana` | Cooldown: `10s`):
  - Emite descarga eletromagnética em toda a base, congelando e desacelerando os robôs por 4 segundos.
- <kbd>W</kbd> **Sobrecarga dos Reatores** (Custo: `45💠 Mana` | Cooldown: `14s`):
  - Concede 2x velocidade de ataque (*Overdrive*) para todas as torres ativas por 6 segundos.
- <kbd>E</kbd> **Bombardeio Tático Orbital** (Custo: `50💠 Mana` | Cooldown: `12s`):
  - Mira precisa onde você clica no mapa, chamando 5 salvas explosivas de mísseis com dano em área devastador.

---

## 🌟 Torres Robóticas & Upgrades Ramificados

1. 🔫 **Gatling Vulcan** (`100⚡`): Metralhadora de alta cadência com recuo elástico e estrelas de disparo.
   - *Ramo A:* **Hyper-Overclock** (+120% cadência extrema).
   - *Ramo B:* **Shredder Balístico** (35% chance de crítico x2.5).
2. 🔦 **Laser Térmico** (`160⚡`): Feixe contínuo lock-on que derrete blindagens.
   - *Ramo A:* **Prisma Tríplice** (ataca até 3 alvos simultâneos).
   - *Ramo B:* **Desintegrador Gravitacional** (+100% dano contínuo).
3. 💣 **Canhão Plasma** (`210⚡`): Morteiro pesado de grande área (AoE).
   - *Ramo A:* **Bombardeio Cluster** (3 submunições explosivas).
   - *Ramo B:* **Nova Incandescente** (campo de chamas por 3s).
4. ❄️ **Pulso PEM Criogênico** (`150⚡`): Ondas de desaceleração e quebra de escudos.
   - *Ramo A:* **Zero Absoluto** (chance de congelamento total).
   - *Ramo B:* **Descarga Eletrostática** (dano de choque contínuo).
5. ⚡ **Arco Voltaico Tesla** (`240⚡`): Relâmpagos encadeados em zigue-zague.
   - *Ramo A:* **Tempestade de Cadeia** (salta em até 7 alvos com dano amplificado).
   - *Ramo B:* **Bobina de Ressonância** (acelera torres vizinhas em +25%).

---

## 🕹️ Controles

| Comando | Teclado | Ação |
| :--- | :--- | :--- |
| **Defesas 1 a 5** | <kbd>1</kbd>, <kbd>2</kbd>, <kbd>3</kbd>, <kbd>4</kbd>, <kbd>5</kbd> | Seleciona a torre para construir |
| **Construir / Inspecionar** | <kbd>Clique com o Botão Esquerdo</kbd> | Posiciona torre nas bases ou abre painel de inspeção |
| **Habilidade PEM** | <kbd>Q</kbd> | Aciona o Pulso PEM global |
| **Habilidade Overdrive** | <kbd>W</kbd> | Ativa a sobrecarga 2x de velocidade |
| **Ataque Orbital** | <kbd>E</kbd> | Ativa a mira de bombardeio orbital |
| **Próxima Onda** | <kbd>Barra de Espaço</kbd> | Inicia a onda |

---

## 🌐 Publicação no GitHub

Para salvar e enviar as atualizações com o novo mapa:
```bash
git add .
git commit -m "feat: Official lunar map background, aligned conveyor path, and balanced energy/mana system"
git push origin main
```

Jogue online no seu GitHub Pages:
👉 **[https://jgscarioca.github.io/GAME-DE-NAVE/](https://jgscarioca.github.io/GAME-DE-NAVE/)**
