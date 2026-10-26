# Estilo Visual da HQ — Ecos de Nós

**Grupo:** Fora de Órbita
**Integrantes:** Amábile Evangelista Kosloski, Mariana Alexandre Alves Amourim, Pedro Marques Machado
**Tema:** Distopia e ficção científica com romance e mistério
**Issue relacionada:** #3 (PB03 — Escolher a ferramenta de IA e definir o estilo visual)

---

## Atualização da PB13

A versão atual adota **mangá colorido**, com rostos estilizados, olhos expressivos, contornos marcados e sombras simples. O uso de mangá não significa retirar as cores. Os registros iniciais de Gemini abaixo são históricos; os documentos PB09 e PB11 registram uso posterior de ChatGPT.

As fichas e os prompts de referência foram alinhados aos protagonistas adultos e aos uniformes de manutenção. As roupas casuais das gravações e do desfecho são exceções intencionais à regra de uniformes.

## 1. Ferramenta escolhida inicialmente

**Nome:** Gemini (Google)

**Motivo da escolha:** Ferramenta gratuita, fácil de usar por quem não tem experiência com IA, acessível a todos os integrantes da equipe com uma conta Google, e capaz de gerar imagens a partir de descrições em texto.

---

## 2. Definição de estilo

| Item | Definição |
|---|---|
| **Traço** | Quadrinhos de ficção científica com contorno preto definido e sombreamento em cel-shading (sombras simples, sem degradê pesado) |
| **Clima** | Distopia esperançosa, ruínas tomadas pela natureza |
| **Proporção** | 4:3 horizontal para os quadros (ou 3:4 vertical, caso o grupo opte por páginas de HQ) |
| **Enquadramento padrão** | Plano médio, com cenários detalhados o suficiente para contextualizar a cena |

### 2.1 Paleta de cores por ambiente

A história se passa em dois mundos, e a paleta conta visualmente a virada da narrativa.

| Ambiente | Cores | Iluminação |
|---|---|---|
| **Estação suspensa** | Tons frios e metálicos: cinza, azul-aço, ciano | Luz artificial fria e dura |
| **Superfície do planeta** | Ferrugem, concreto, céu alaranjado | Luz natural suave, tom de pôr do sol |
| **Jardim** | Verde vivo, dourado, laranja | Luz natural dourada, em forte contraste com o resto |

### 2.2 Regra de cores dos personagens

- **Nina:** sempre em **verde** (uniforme verde-musgo).
- **Ravi:** sempre em **azul** (uniforme azul com detalhes cinza).
- A regra vale em todos os cenários, na estação e na superfície.

---

## 3. Prompt base de estilo

Colar no início de **todo** prompt de imagem. A ordem de cada prompt é: **estilo base + personagem + cenário + ação/emoção**.

```
Science fiction dystopian comic book style, clean bold black
outlines, cel-shaded coloring, detailed backgrounds.
Color palette: cold metallic tones (steel blue, grey, cyan) for
the space station scenes; warm natural tones (lush green, golden
yellow, sunset orange) for the planet surface and garden scenes.
Lighting: harsh artificial light on the station, soft golden
natural light on the surface.
Framing: medium shot, 4:3 horizontal panel.
Rules: keep the characters' appearance exactly as the reference
sheets (hair, skin tone, uniform colors), no text in the image,
no watermark.
```

---

## 4. Personagens

> **Nota de atualização:** as fichas originais (PB02) e os prompts da PB05 descreviam adolescentes em um contexto escolar (mochila amarela, camiseta, moletom), o que não combina com a história, que mostra adultos responsáveis pela manutenção de máquinas em uma estação suspensa. As descrições abaixo mantêm cabelo, olhos, pele e a regra de cores originais, e adaptam idade e roupas.

### 4.1 Nina

- **Aparência:** adulta jovem, cabelo cacheado castanho-escuro até o ombro, olhos escuros, pele parda, estatura média.
- **Roupas:** uniforme de manutenção verde-musgo com bolsos de ferramentas, botas resistentes e luvas de trabalho.
- **Personalidade:** curiosa, analítica, determinada, preocupada com meio ambiente e sustentabilidade.

**Prompt:**

```
Young adult Brazilian woman, brown skin, shoulder-length curly
dark brown hair, dark eyes, medium height, wearing a moss-green
maintenance jumpsuit with tool pockets, sturdy boots and work
gloves, curious and determined expression, science fiction
dystopian comic art style, character reference sheet.
```

### 4.2 Ravi

- **Aparência:** adulto jovem, alto, cabelo curto liso preto, olhos castanhos, pele clara.
- **Roupas:** uniforme de manutenção azul com detalhes cinza, botas resistentes e cinto de ferramentas.
- **Personalidade:** prático, criativo, bem-humorado e tecnológico.

**Prompt:**

```
Young adult man, light skin, short straight black hair, brown
eyes, tall, wearing a blue maintenance jumpsuit with grey
details, sturdy boots and tool belt, relaxed and slightly
humorous expression, science fiction dystopian comic art style,
character reference sheet.
```

---

## 5. Cenários principais

Gerar uma folha de referência para cada cenário e reaproveitá-la nas cenas seguintes.

| Cenário | Descrição para o prompt |
|---|---|
| **Estação suspensa** | Corredores metálicos, painéis luminosos, janelas com vista para um planeta cinza e nublado |
| **Superfície** | Ruínas de concreto, ferrugem, máquinas de extração ao fundo, céu alaranjado |
| **Jardim** | Vegetação densa e viva entre ruínas, luz dourada, contraste forte com o restante |

---

## 6. Diretrizes de consistência

1. Gerar primeiro a folha de referência de cada personagem e **reaproveitar essas imagens** como referência em todas as cenas.
2. Usar sempre o mesmo prompt base de estilo (seção 3), sem alterações.
3. Manter a regra de cores: verde para Nina, azul para Ravi.
4. Gerar de 3 a 4 variações de cada quadro e escolher a que melhor mantém a aparência dos personagens.
5. Guardar os prompts que funcionaram para reaproveitar nas PB06, PB08 e PB09.

---

## 7. Padrão de nomes de arquivos

```
cenaXX-quadroYY.png
```

Exemplos: `cena01-quadro01.png`, `cena07-quadro03.png`

Organização sugerida de pastas:

```
imagens/
├── personagens/
├── cenarios/
├── sequencia-inicial/
└── cenas-restantes/
```

---

## 8. Observações

_(Preencher após os testes: limitações da ferramenta, dicas para manter a consistência, problemas recorrentes e como foram resolvidos.)_
