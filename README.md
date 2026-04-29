# 📸 Calculadora de Precificação — Fotografia & Vídeo

Esta é uma ferramenta profissional desenvolvida para fotógrafos e profissionais de imagem que desejam calcular orçamentos precisos com base em custos reais, horas de trabalho e posicionamento de mercado.

## 🚀 Sobre o Projeto

A **Calculadora de Precificação** permite que o utilizador selecione o seu nicho de mercado (desde Casamentos a Eventos Corporativos) e ajuste variáveis como horas de ensaio, tempo de edição e quilometragem para obter uma sugestão de preço final competitiva e lucrativa.

## ✨ Funcionalidades Principais

* **Lógica por Nicho:** Valores base de hora técnica ajustados para diferentes áreas (Família, Casamento, Corporativo, etc.).
* **Cálculo de Margem Real:** Define a tua margem de lucro sobre os custos operacionais totais.
* **Comparador de Mercado:** Gráfico interativo que compara o teu preço sugerido com a média nacional atualizada para 2026.
* **Custo de Deslocação:** Cálculo automático baseado na distância percorrida.
* **Design Premium:** Interface moderna, responsiva e com suporte a modo escuro, utilizando Tailwind CSS.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web padrão, garantindo leveza e portabilidade:

* **HTML5** (Estrutura Semântica)
* **Tailwind CSS** (Estilização Responsiva e Moderna)
* **JavaScript** (Lógica de Cálculo Dinâmica)
* **Google Fonts** (Tipografia Montserrat para legibilidade)

## 📦 Como Utilizar

### Localmente
1. Faça o download ou clone este repositório.
2. Abra o ficheiro `calculadora.html` em qualquer navegador moderno.

### Online (GitHub Pages)
Para colocar o site online de forma permanente:
1. Vá às **Settings** no seu repositório do GitHub.
2. Aceda à aba **Pages**.
3. Em "Build and deployment", selecione a branch `main` e clique em **Save**.
4. O link será gerado automaticamente pelo GitHub.

## ⚙️ Personalização

Para ajustar as taxas horárias ou as médias de mercado, basta editar o objeto `config` dentro do código JavaScript no ficheiro HTML. O bloco de código abaixo deve ser editado conforme a sua necessidade:

```javascript
const config = {
    'Teu Nicho': { 
        valorHora: 200, 
        custoKm: 1.10, 
        margem: 40, 
        mercMin: 1000, 
        mercMax: 3000, 
        hint: 'Descrição do nicho aqui.' 
    }
};
