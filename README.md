# A Arca de Noé — modelo 3D interativo

Modelo 3D da Arca de Noé feito a partir de Gênesis 6–9, com cálculos ao vivo, citações bíblicas e uma separação clara entre o que o texto diz, o que é interpretação e o que é hipótese do modelo. Há uma versão em português (raiz) e outra em inglês (`en/`).

**Site:** `https://<usuario>.github.io/<repositorio>/` · **English:** `https://<usuario>.github.io/<repositorio>/en/`

## O que tem no site

- **Modelo 3D navegável** (Three.js r128):
  - vistas Exterior, Corte e Raio‑X, com filtro por andar;
  - nomes das partes clicáveis;
  - ângulos prontos (da água, do alto, de frente, escala humana);
  - **comparação de tamanho** com o Titanic, um campo de futebol, um avião grande, um prédio de 10 andares e uma pessoa.
- **Duas formas de casco:**
  - **Caixa:** a forma inicial, leitura literal de Gn 6:15;
  - **Navio:** reconstrução moderna, sem fonte antiga.
  - Os cálculos seguem a forma escolhida.
- **Caminhar dentro** em primeira pessoa (teclado e mouse; joystick no celular), com minimapa, cartões explicativos e a possibilidade de **olhar pela janela** do 3º andar.
- **Tour guiado** com 16 paradas.
- **Linha do tempo:**
  - dia a dia, com **dia e noite** na velocidade lenta;
  - o corvo e a pomba voando no 3D;
  - o arco‑íris no fim;
  - **duas contagens do calendário** (meses de 30 dias ou ano lunar).
- **Teste de tempestade:**
  - curva de estabilidade calculada por fatias do casco inclinado;
  - ângulo em que a água chega à janela e ângulo em que a arca vira;
  - animação que aumenta as ondas até alagar ou virar.
- **Construa a sua arca:** mude as medidas (ou use as formas de Gilgamesh e da Tábua de Finkel) e veja se flutua, se é estável, até onde aguenta inclinar e se cabem os animais.
- **Cálculos:**
  - volume e arqueação;
  - deslocamento e estabilidade;
  - calado em metros e calado de equilíbrio pelo peso;
  - calculadora **"Cabiam os animais?"**.
- **Versões antigas** na mesma escala, mais **Onde a arca pousou**.
- **Contexto:**
  - palavras hebraicas difíceis (*tēbâ*, *gōper*, *qinnîm*, *kōper*, *ṣōhar*, *ʾammâ*, *mîn*);
  - relatos de dilúvio de outros povos;
  - mapa esquemático da região.
- **Por quê?**: explica cada escolha do modelo.
- **Link compartilhável**, com a forma, o dia, o côvado, a aba e o ângulo escolhidos.
- **Imagem de prévia** para WhatsApp e LinkedIn (`preview.png`).

## Limites

- Não há evidência arqueológica verificada da arca. O site modela o que o texto descreve e testa a coerência física das medidas. Ele não afirma nem nega a historicidade do relato.
- Proa, quilha, baias, rampas, lamparinas, animais, clima, sons, trajetos das aves, peso, carga, calado de equilíbrio e testes de tempestade são hipóteses ou ilustração, e estão marcados assim no site.
- A física trata o casco como um corpo rígido e não testa a resistência da madeira.

## Fontes

- **Texto bíblico:**
  - Tradução Brasileira (1917), em domínio público (versão em português);
  - World English Bible, em domínio público (versão em inglês).
- As demais fontes estão listadas na aba **Fontes** do site.

## Como publicar (GitHub Pages)

1. Coloque na raiz do repositório os arquivos `index.html`, `README.md` e `preview.png`, mais a pasta `en/` com o seu `index.html`.
2. Em `index.html` e `en/index.html`, troque `SEU-USUARIO` pelo seu usuário do GitHub nas linhas `og:url` e `og:image`.
3. Vá em Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. Em cerca de um minuto, o site estará em `https://<usuario>.github.io/<repositorio>/`.

Não há build nem dependências locais: Three.js e as fontes vêm de CDN.
