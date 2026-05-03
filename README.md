Sol Turismo - Site de Viagens

**Descrição**

Site de viagem responsivo desenvolvido como landing page para a agência **Sol Turismo**. A página apresenta uma experiência visual atrativa com banner destacado, navegação interna e informações sobre destinos.

**Funcionalidades Principais**

- **Banner Interativo**: Imagem de fundo com texto overlay (Gramado/RS)
- **Navegação Fixa**: Menu no topo com links internos para as seções
- **Seções Informativas**:
  - **MinhaViagem**: Informações sobre pacotes e destinos em destaque
  - **NosEncontre**: Dados de contato da agência
  - **Conselhos**: Dicas essenciais para viajantes
- **Design Responsivo**: Adaptado para diferentes tamanhos de tela
- **Visual Aprimorado**: Cores harmônicas, sombras de texto e efeitos hover

**Estrutura do Projeto**

```
Site Viagens/
├── index.html          # Arquivo principal HTML
├── style.css           # Estilos e layout
├── README.md           # Este arquivo
└── ../cidade-de-gramado-rs.avif  # Imagem do banner
```

**Design e Cores**

- **Paleta de Cores**:
  - Navegação: `#3813bd` (roxo)
  - Títulos (h2): `#3813bd` com sombra amarela
  - Banner h1: Laranja com sombra preta
  - Banner p: Preto com fundo branco e sombra laranja
  - Links hover: Transição suave para roxo escuro

**Responsividade**

O site é otimizado para dispositivos móveis com breakpoint em 768px, redimensionando:
- Fonte do h1 do banner (3em → 2em)
- Fonte do parágrafo do banner (1.5em → 1.2em)
- Menu será reorganizado em versões futuras

## Como Usar

1. **Abrir o site**: Clique duas vezes em `index.html` ou abra em um navegador web
2. **Navegar**: Use o menu no topo para ir para cada seção
3. **Encontrar informações**:
   - Home: Volta ao banner
   - Minha Viagem: Destinos e pacotes
   - Nos Encontre: Contato e comunicação
   - Conselhos: Dicas para sua viagem

## Detalhes Técnicos

### HTML Semântico
- Uso de tags apropriadas: `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- IDs internos para navegação com âncoras (`#`)

### CSS
- Flexbox para layout responsivo
- Transições suaves (0.3s) nos efeitos hover
- Text-shadow para melhor legibilidade
- Background-image com cover para o banner

### Sem JavaScript
O projeto funciona completamente sem JavaScript, usando apenas HTML e CSS semântico.

**Notas de Desenvolvimento**

- A imagem Do banner (Gramado/RS) é carregada como URL relativa
- Navegação com foco em UX: links internos sem abrir novas abas
- Padding-bottom do banner (50px) para compensar a navegação fixa

**Melhorias Futuras**

- Adicionar mais destinos com imagens
- Formulário de contato funcional
- Galeria de fotos interativa
- Integração com redes sociais
- Sistema de reservas online

---

**Desenvolvido com ❤️ para Sol Turismo**

*Última atualização: Maio de 2026*
