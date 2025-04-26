
# 📚 Estrelas do Amanhã - Formulário de Matrícula

Projeto de um formulário de matrícula para a escola de educação infantil **Estrelas do Amanhã**, focado em acessibilidade, responsividade e experiência do usuário.

## ✨ Sobre o Projeto

Este projeto é um formulário completo de inscrição, dividido em seções claras:
- Informações da criança
- Endereço residencial
- Informações do responsável
- Opções de matrícula (turno e esporte)
- Aceite de termos e condições

O layout é clean e intuitivo, seguindo boas práticas de UX/UI.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica do conteúdo
- **CSS3** (puro): Estilização moderna com `grid layout`, `flexbox` e `:has()` para interações avançadas
- **Google Fonts**: Tipografia `Poppins`
- **SVG Icons**: Ícones vetoriais para tornar a experiência mais visual
- **Responsividade**: Layout adaptado para diferentes tamanhos de tela
- **Validações básicas**: Campos obrigatórios e feedback visual de erro

## 🎨 Layout

O projeto conta com dois painéis principais:
- **Formulário**: Área de preenchimento
- **Aside**: Mensagem institucional com imagem ilustrativa fixo na janela

A estrutura é feita com `grid`:
```css
#app {
  display: grid;
  grid-template-columns: 51.25% 48.75%;
  height: 100vh;
}
