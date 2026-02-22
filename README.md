# 🥋 Associação Punho de Aço

Site moderno e responsivo para academia de artes marciais especializada em Hapkido, localizada em Marabá - Pará - Brasil.

![Status](https://img.shields.io/badge/Status-Completo-success)
![Responsivo](https://img.shields.io/badge/Design-Responsivo-blue)
![Mobile First](https://img.shields.io/badge/Mobile-First-blueviolet)

---

## 📋 Sobre o Projeto

O site da **Associação Punho de Aço** foi desenvolvido para apresentar a academia de Hapkido do Mestre Germano, oferecendo uma experiência moderna, profissional e inspiradora para potenciais alunos interessados em defesa pessoal e artes marciais.

### 🎯 Objetivo

Criar uma presença online profissional que:
- Apresente a academia e seus valores
- Destaque os benefícios do Hapkido
- Facilite o contato via WhatsApp para aulas experimentais
- Funcione perfeitamente em dispositivos móveis (prioridade)

---

## ✨ Características

### 🎨 Design
- **Paleta de cores**: Preto, azul escuro e azul neon
- **Estilo**: Minimalista, elegante e moderno
- **Tipografia**: Russo One (títulos) + Rajdhani (corpo)
- **Animações**: Suaves e profissionais ao rolar a página

### 📱 Responsividade
- ✅ **Mobile First** - Prioridade máxima para celulares
- ✅ Tablet - Layout adaptado para telas médias
- ✅ Desktop - Experiência completa em telas grandes
- ✅ Breakpoints otimizados: 480px, 768px, 1200px

### 🚀 Funcionalidades

1. **Hero Section Impactante**
   - Imagem de fundo de treino de Hapkido
   - Título e subtítulo animados
   - Botão de CTA para WhatsApp
   - Indicador de scroll animado

2. **Seção Sobre a Academia**
   - Placeholder para foto da academia
   - Descrição institucional
   - Localização destacada

3. **Seção Sobre o Mestre**
   - Placeholder para foto do Mestre Germano
   - Informações profissionais
   - Badge de certificação

4. **Benefícios do Hapkido**
   - 6 cards animados com ícones:
     - Defesa pessoal
     - Disciplina
     - Condicionamento físico
     - Autoconfiança
     - Controle emocional
     - Coordenação motora
   - Efeito hover 3D nos cards

5. **História do Hapkido**
   - Resumo introdutório
   - Modal interativo com história completa
   - Animações suaves de abertura/fechamento
   - Fecha ao clicar fora ou pressionar ESC

6. **Planos e Valores**
   - Card destacado central
   - Preço: R$ 84,00/mês
   - Badge: "Aula experimental gratuita"
   - Animação do contador de preço
   - Botão WhatsApp integrado

7. **Rodapé Completo**
   - Informações da academia
   - Links rápidos para navegação
   - Botão de contato WhatsApp
   - Ícones de redes sociais
   - Copyright

8. **Botão Flutuante WhatsApp**
   - Fixo no canto inferior direito
   - Animação de pulso
   - Sempre acessível

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna
  - Flexbox e Grid Layout
  - CSS Variables (Custom Properties)
  - Media Queries responsivas
  - Animações e transições
- **JavaScript (Vanilla)** - Interatividade
  - Intersection Observer API
  - Event Listeners
  - DOM Manipulation
  - Smooth Scroll

### Bibliotecas Externas (via CDN)
- **Font Awesome 6.4.0** - Ícones vetoriais
- **Google Fonts** - Tipografia (Russo One, Rajdhani)

---

## 📂 Estrutura de Arquivos

```
associacao-punho-de-aco/
│
├── index.html              # Página principal
├── css/
│   └── style.css          # Estilos completos e responsivos
├── js/
│   └── script.js          # Funcionalidades JavaScript
└── README.md              # Documentação do projeto
```

---

## 🎯 Seções do Site

### 1. Header / Navegação
- Logo animado
- Menu responsivo com hamburguer (mobile)
- Links âncora para todas as seções
- Efeito de sombra ao rolar

### 2. Hero (Início) - `#inicio`
- Título principal: "ASSOCIAÇÃO PUNHO DE AÇO"
- Subtítulo: "HAPKIDO — DEFESA PESSOAL, DISCIPLINA E CONTROLE"
- CTA: "COMEÇAR" (abre WhatsApp)

### 3. Sobre a Academia - `#sobre`
- Foto placeholder da academia
- Texto institucional
- Badge de localização

### 4. Sobre o Mestre - `#mestre`
- Foto placeholder do Mestre Germano
- Nome e cargo
- Descrição profissional
- Badge de certificação

### 5. Benefícios - `#beneficios`
- Grid de 6 cards animados
- Ícones representativos
- Descrições dos benefícios
- Efeito hover 3D

### 6. História do Hapkido - `#historia`
- Resumo introdutório
- Botão "VER MAIS"
- Modal com história completa
- Animações suaves

### 7. Planos - `#planos`
- Card de mensalidade destacado
- Valor: R$ 84,00/mês
- Lista de benefícios
- Badge: "Aula experimental gratuita"
- CTA WhatsApp

### 8. Rodapé - Footer
- Informações da academia
- Links de navegação
- Contato WhatsApp
- Redes sociais
- Copyright

---

## 📞 Integração WhatsApp

### URLs Configuradas

**Mensagem padrão:**
```
"Olá, quero fazer uma aula experimental de Hapkido."
```

**Links WhatsApp no site:**
- Botão Hero "COMEÇAR"
- Botão Planos "COMEÇAR AGORA"
- Botão flutuante (canto inferior direito)
- Link no rodapé

### ⚠️ Configuração Necessária

**IMPORTANTE:** Substitua `5594000000000` pelo número de WhatsApp real da academia no formato:
- Código do país: `55` (Brasil)
- DDD: `94` (Marabá - PA)
- Número: `000000000`

**Exemplo:** `5594991234567`

**Arquivos a editar:**
- `index.html` (todas as ocorrências de `wa.me/5594000000000`)

---

## 🎨 Paleta de Cores

```css
--color-black: #000000           /* Fundo principal */
--color-dark-blue: #0a1628       /* Fundo secundário */
--color-neon-blue: #00d4ff       /* Destaques e CTAs */
--color-neon-glow: rgba(0, 212, 255, 0.5)  /* Brilho neon */
--color-white: #ffffff           /* Texto principal */
--color-gray: #a0a0a0            /* Texto secundário */
--color-dark-gray: #1a1a1a       /* Fundos alternativos */
```

---

## 📸 Placeholders de Imagens

O site possui placeholders estilizados para as seguintes imagens que devem ser substituídas:

1. **Imagem Hero** (linha 50 do index.html)
   - Atualmente: Unsplash placeholder
   - Substitua por: Foto de treino de Hapkido da academia

2. **Foto da Academia** (seção #sobre)
   - Placeholder com ícone e texto
   - Substitua por: Foto externa ou interna da academia

3. **Foto do Mestre Germano** (seção #mestre)
   - Placeholder com ícone e texto
   - Substitua por: Foto profissional do instrutor

### Como substituir imagens:

**Opção 1 - Substituir a tag placeholder por imagem:**
```html
<!-- Antes (placeholder) -->
<div class="image-placeholder">
    <i class="fas fa-university"></i>
    <p>Foto da Academia</p>
</div>

<!-- Depois (imagem real) -->
<img src="caminho/para/foto-academia.jpg" alt="Associação Punho de Aço">
```

**Opção 2 - Usar URL externa:**
```html
<img src="https://seusite.com/imagens/foto.jpg" alt="Descrição">
```

---

## 🚀 Funcionalidades JavaScript

### 1. Menu Mobile (Hamburguer)
- Toggle do menu lateral
- Fecha ao clicar em links
- Animação smooth

### 2. Scroll Animations
- Intersection Observer API
- Elementos aparecem ao entrar na viewport
- Performance otimizada

### 3. Modal da História
- Abre com animação suave
- Fecha com botão X
- Fecha ao clicar fora
- Fecha com tecla ESC
- Previne scroll do body quando aberto

### 4. Smooth Scroll
- Navegação suave entre seções
- Offset para compensar header fixo

### 5. Animação de Cards
- Efeito 3D hover nos benefícios
- Acompanha movimento do mouse

### 6. Contador Animado
- Preço anima de 0 a 84
- Ativa ao entrar na viewport

### 7. Efeito Parallax
- Hero image com movimento sutil
- Melhora profundidade visual

---

## 📱 Responsividade Detalhada

### Mobile (< 480px)
- Menu hamburguer ativo
- Layout de coluna única
- Botões e fontes otimizados
- Espaçamentos reduzidos
- Imagens adaptadas

### Tablet (481px - 768px)
- Menu hamburguer mantido
- Algumas seções em grid
- Espaçamento intermediário
- Cards em 2 colunas

### Desktop (> 768px)
- Menu horizontal completo
- Layout em grid completo
- Espaçamentos generosos
- Efeitos hover ativos
- Cards em 3 colunas

---

## ✅ Checklist de Implementação

### Estrutura
- [x] HTML5 semântico
- [x] Meta tags configuradas
- [x] Favicon (pode adicionar)
- [x] Links CDN funcionais

### Design
- [x] Paleta de cores aplicada
- [x] Tipografia profissional
- [x] Layout responsivo
- [x] Animações suaves
- [x] Efeitos hover

### Funcionalidades
- [x] Menu mobile funcional
- [x] Modal da história
- [x] Scroll suave
- [x] Animações ao scroll
- [x] WhatsApp integrado
- [x] Botão flutuante

### Otimizações
- [x] Performance otimizada
- [x] Lazy loading preparado
- [x] Código limpo e comentado
- [x] SEO básico

---

## 🔧 Próximos Passos Recomendados

### Conteúdo
1. **Substituir placeholders de imagens**
   - Foto da academia
   - Foto do Mestre Germano
   - Imagem hero (treino de Hapkido)

2. **Atualizar número WhatsApp**
   - Substituir `5594000000000` pelo número real
   - Testar links em dispositivo móvel

3. **Adicionar links de redes sociais**
   - Facebook da academia
   - Instagram da academia
   - YouTube (se houver)

### Melhorias Técnicas
1. **Adicionar Favicon**
   ```html
   <link rel="icon" type="image/png" href="favicon.png">
   ```

2. **Otimizar imagens**
   - Comprimir fotos para web
   - Usar formatos modernos (WebP)
   - Implementar lazy loading

3. **Analytics**
   - Google Analytics para rastreamento
   - Google Tag Manager
   - Facebook Pixel (se houver)

4. **SEO Avançado**
   - Open Graph tags
   - Twitter Cards
   - Schema.org markup
   - Sitemap.xml

5. **PWA (Progressive Web App)**
   - Manifest.json
   - Service Worker
   - Funcionalidade offline

### Recursos Adicionais
1. **Galeria de Fotos**
   - Seção com fotos de treinos
   - Lightbox para visualização

2. **Depoimentos**
   - Feedback de alunos
   - Carousel de depoimentos

3. **Horários de Aula**
   - Tabela de horários
   - Calendário interativo

4. **Blog/Notícias**
   - Artigos sobre Hapkido
   - Notícias da academia
   - Eventos

5. **Formulário de Contato**
   - Alternativa ao WhatsApp
   - Integração com e-mail

---

## 📧 Contato da Academia

**Associação Punho de Aço**  
📍 Marabá — Pará — Brasil  
🥋 Hapkido Defesa Pessoal  
👨‍🏫 Instrutor: Mestre Germano  

📱 **WhatsApp:** [Atualizar número]  
📘 **Facebook:** [Adicionar link]  
📸 **Instagram:** [Adicionar link]  
🎥 **YouTube:** [Adicionar link]  

---

## 📄 Licença

© 2026 Associação Punho de Aço. Todos os direitos reservados.

---

## 🎖️ Créditos

**Desenvolvimento:** Site criado com foco em performance, design moderno e experiência do usuário.

**Tecnologias:**
- HTML5, CSS3, JavaScript (Vanilla)
- Font Awesome 6.4.0
- Google Fonts (Russo One, Rajdhani)

**Imagens:**
- Hero background: Unsplash (temporário - substituir)
- Placeholders: Ícones Font Awesome

---

## 🆘 Suporte

Para dúvidas ou suporte sobre o site:
1. Verifique a documentação acima
2. Revise os comentários no código
3. Teste em diferentes dispositivos
4. Valide HTML e CSS

---

## 📊 Status do Projeto

| Componente | Status | Observações |
|-----------|--------|-------------|
| HTML | ✅ Completo | Estrutura semântica |
| CSS | ✅ Completo | Responsivo e animado |
| JavaScript | ✅ Completo | Todas funcionalidades |
| WhatsApp | ⚠️ Configurar | Atualizar número |
| Imagens | ⚠️ Pendente | Substituir placeholders |
| Redes Sociais | ⚠️ Pendente | Adicionar links |
| SEO | ✅ Básico | Otimizar ainda mais |
| Performance | ✅ Otimizado | Lazy loading preparado |

---

## 🎯 Objetivos Alcançados

✅ Site moderno e profissional  
✅ Design minimalista e elegante  
✅ 100% responsivo (mobile-first)  
✅ Animações suaves e profissionais  
✅ Modal funcional da história  
✅ Integração WhatsApp  
✅ Menu mobile com hamburguer  
✅ Botão flutuante WhatsApp  
✅ Scroll suave entre seções  
✅ Cards animados de benefícios  
✅ Layout adaptável (mobile/tablet/desktop)  
✅ Código limpo e comentado  
✅ Performance otimizada  

---

**Desenvolvido com 🥋 para a Associação Punho de Aço**
