# Documentação da Landing Page - AEG Proteção

## 1. Visão Geral
Landing page para serviços de proteção veicular com foco em conversão de leads. Desenvolvida com tecnologias modernas e responsivas.

### Características Principais:
- Design moderno e profissional
- Totalmente responsivo
- Animações e interações suaves
- Formulário de captação de leads
- Seção de FAQ interativa
- Integração com redes sociais
- Botão flutuante de WhatsApp

## 2. Estrutura do Arquivo
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <!-- Metadados e recursos externos -->
</head>
<body>
    <!-- Conteúdo da página -->
</body>
</html>
```

## 3. Dependências
| Recurso | Descrição |
|---------|-----------|
| Tailwind CSS | Framework CSS utilitário via CDN |
| Font Awesome | Ícones via CDN |
| Google Fonts | Fonte Poppins |
| animate.css | Animações (embutidas no estilo) |

## 4. Seções Principais

### 4.1 Header/Navegação
- Logo com ícone
- Menu desktop responsivo
- Menu mobile com animação
- Transições suaves

### 4.2 Hero Section
- Gradiente azul dinâmico
- Chamada principal com CTA
- Animação de carro
- Badge de economia

### 4.3 Trust Badges
- Selos de confiança:
  - Veículos protegidos
  - Atendimento 24h
  - Cobertura nacional

### 4.4 Benefícios
- Grid de 6 cards com:
  - Ícones ilustrativos
  - Efeito hover
  - Descrições claras

### 4.5 Como Funciona
- Processo em 4 etapas
- Ícones numerados
- Layout side-by-side

### 4.6 Depoimentos
- Cards de testemunhos reais
- Classificação por estrelas
- Fotos de perfil

### 4.7 CTA
- Chamada final de ação
- Botão destacado

### 4.8 Formulário de Contato
- Dois painéis:
  - Informações de contato
  - Formulário de lead
- Validação básica
- Links para redes sociais

### 4.9 FAQ
- Acordeão interativo
- Perguntas frequentes
- Animações de abertura/fechamento

### 4.10 Footer
- 4 colunas responsivas
- Links úteis
- Formulário de newsletter
- Informações de contato
- Redes sociais

## 5. Funcionalidades JavaScript
```javascript
// Mobile Menu
function openMobileMenu() { ... }
function closeMobileMenu() { ... }

// Form Submission
document.getElementById("leadForm").addEventListener("submit", ... )

// FAQ Toggle
document.querySelectorAll('.faq-toggle').forEach(...)

// Smooth Scroll
document.querySelectorAll('a[href^="#"]').forEach(...)
```

## 6. Personalização
### 6.1 Cores
Modificar no CSS as variáveis:
- `hero-gradient`
- `text-blue-600` (cor principal)
- `bg-blue-600` (botões)

### 6.2 Conteúdo
Atualizar:
- Textos nas seções
- Números de telefone/e-mail
- Links de redes sociais
- Imagens (carro, ícones)

### 6.3 Formulário
Configurar:
- Endpoint de envio
- Campos adicionais
- Mensagens de sucesso/erro

## 7. Responsividade
- Breakpoints: md (768px) e lg (1024px)
- Layouts adaptativos:
  - Menu hamburger em mobile
  - Grid columns responsivas
  - Imagens dimensionáveis
