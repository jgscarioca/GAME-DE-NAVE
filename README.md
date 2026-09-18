# ⚡ CYBER CORE: MECHA TOWER DEFENSE

Um jogo tático de **Tower Defense** em alta definição com temática robótica e estética cyberpunk neon, desenvolvido em **HTML5 Canvas**, **Vanilla CSS** e **Web Audio API** procedural nativo (sem dependências pesadas).

Defenda o **Núcleo Quântico Central** contra 20 levas implacáveis de exércitos cibernéticos, drones autônomos, mechas blindados e Titãs chefões colossais!

---

## 🌟 Principais Recursos

- **5 Sistemas Defensivos Robóticos Especializados**:
  - 🔫 **Gatling Vulcan**: Projéteis cinéticos contínuos de alta cadência, devastadores contra enxames de batedores.
  - 🔦 **Laser Térmico**: Feixe contínuo lock-on de alta energia que aquece e perfura as armaduras mais espessas.
  - 💣 **Canhão Plasma**: Disparos de trajetória parabólica com colossal área de explosão (AoE).
  - ❄️ **Pulso PEM Criogênico**: Ondas de choque eletromagnéticas que desaceleram e neutralizam os robôs.
  - ⚡ **Arco Voltaico Tesla**: Relâmpagos encadeados em alta voltagem que saltam entre múltiplos alvos em sequência.

- **Sistema Profundo de Upgrades e Ramificação (Nível 1 ao 4)**:
  - **Níveis 1 a 3**: Progressão contínua de dano, alcance e cadência de fogo.
  - **Protocolo Supremo (Nível 4 - Branching Upgrades)**: Escolha entre duas especializações exclusivas por torre:
    - *Gatling*: **Hyper-Overclock** (+120% cadência) ou **Shredder Balístico** (dano crítico x2.5).
    - *Laser*: **Prisma Tríplice** (dispara em 3 alvos ao mesmo tempo) ou **Desintegrador Gravitacional** (+100% dano).
    - *Canhão*: **Bombardeio Cluster** (gera 3 submunições) ou **Nova de Plasma Incandescente** (campo de chamas).
    - *PEM*: **Zero Absoluto** (chance de congelar totalmente) ou **Descarga Eletrostática** (dano por choque contínuo).
    - *Tesla*: **Tempestade de Cadeia** (até 7 alvos com amplificação) ou **Bobina de Ressonância** (acelera torres vizinhas em +25%).

- **Habilidades Táticas do Comandante**:
  - <kbd>Q</kbd> **Pulso PEM Global**: Paralisa e danifica todos os robôs na arena por 4 segundos.
  - <kbd>W</kbd> **Sobrecarga dos Reatores (Overdrive)**: Dobra a cadência de fogo de todas as defesas por 6 segundos.
  - <kbd>E</kbd> **Bombardeio Orbital de Mísseis**: Ataque cirúrgico direcionado com o cursor no mapa.

- **Matriz de Pesquisa Tecnológica do Núcleo (Nanitas)**:
  - Invista Nanitas coletadas dos inimigos para desbloquear:
    - *Reator Auxiliar* (geração de créditos por segundo).
    - *Matriz de Precisão* (+% de chance crítica geral).
    - *Nanoreparo de Emergência* (recuperação de integridade do Núcleo entre as ondas).
    - *Antena de Reconhecimento* (+% de alcance global).

- **Áudio Procedural em Tempo Real (Web Audio API)**:
  - Efeitos de sintetizador 100% nativos sem necessidade de downloads ou carregamentos externos.

- **Interface Tática Responsiva**:
  - Suporte completo a mouse e atalhos no teclado no PC e controles adaptados para telas sensíveis ao toque (Mobile/Tablet).
  - Controle de velocidade da partida (<kbd>1x</kbd> e <kbd>2x</kbd>).

---

## 🕹️ Controles e Atalhos

| Comando | Teclado | Ação |
| :--- | :--- | :--- |
| **Defesas 1 a 5** | <kbd>1</kbd>, <kbd>2</kbd>, <kbd>3</kbd>, <kbd>4</kbd>, <kbd>5</kbd> | Seleciona o tipo de torre para construir |
| **Construir / Inspecionar** | <kbd>Clique com o Botão Esquerdo</kbd> | Constrói torre na base ou abre painel de inspeção |
| **Habilidade PEM** | <kbd>Q</kbd> | Aciona o Pulso PEM global |
| **Habilidade Overdrive** | <kbd>W</kbd> | Ativa a sobrecarga das torres |
| **Ataque Orbital** | <kbd>E</kbd> | Ativa a mira de bombardeio orbital |
| **Próxima Onda** | <kbd>Barra de Espaço</kbd> | Inicia a onda de inimigos |

---

## 🚀 Como Jogar e Publicar no GitHub

### Executando Localmente
Basta abrir o arquivo [index.html](file:///c:/Users/jgsca/.gemini/antigravity-ide/scratch/space-shooter/index.html) em qualquer navegador moderno ou rodar um servidor web local:

```bash
# Via Python
python -m http.server 8080

# Ou via Node.js
npx serve .
```

### Publicando no seu Repositório do GitHub
Para sincronizar as alterações e jogar online gratuitamente:

```bash
git add .
git commit -m "feat: Cyber Core Robotic Tower Defense with branching upgrades and orbital abilities"
git push origin main
```

### Ativando o GitHub Pages
1. Acesse o seu repositório no GitHub: `https://github.com/jgscarioca/GAME-DE-NAVE` (ou o nome do seu projeto).
2. Vá em **Settings** > **Pages**.
3. Em **Branch**, selecione `main` e a pasta `/(root)`.
4. Clique em **Save**.
5. Em instantes, o link público do jogo estará disponível para jogar direto no navegador em qualquer dispositivo!
