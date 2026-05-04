# DermaCare - Landing Page para Dermatologista

Uma landing page profissional, moderna e responsiva para uma clínica dermatológica.

## 📋 Estrutura do Projeto

```
templateSite2/
├── index.html              # Página principal
├── README.md               # Documentação
├── css/
│   ├── reset.css          # Normalização de estilos
│   ├── global.css         # Estilos globais e variáveis
│   └── components/
│       ├── header.css     # Estilos do header e navegação
│       └── footer.css     # Estilos do footer
└── image/
    ├── favicon/           # Ícone do site
    └── photo/             # Imagens do site
```

## 🎨 Seções da Landing Page

### 1. **Header**
- Logo da clínica (DermaCare)
- Navegação com links para seções principais
- Botão "Agendar Consulta" destacado

### 2. **Hero Section**
- Título impactante
- Descrição da clínica
- Chamada para ação principal
- Espaço para imagem principal

### 3. **Sobre a Dra. Exemplo**
- Apresentação da profissional
- Credenciais e experiência
- Imagem da doutora

### 4. **Serviços**
- 6 cards com principais serviços
- Ícones em emoji / Possibilidade para trocar por icones.svg
- Hover com efeito de elevação
- Serviços de Exemplo: Consulta, Tratamentos Estéticos, Cuidados Preventivos, Acne, Peeling, Laser

### 5. **Testemunhos**
- 3 depoimentos de pacientes
- Avaliação em estrelas / Em emoji, mas pode ser substituida por imagem.svg
- Design elegante em cards

### 6. **Contato**
- Informações de localização
- Telefone, WhatsApp e Email
- Horário de atendimento
- Maps do google

### 7. **Footer**
- Informações da clínica
- Links rápidos
- Redes sociais
- Copyright

## 🎯 Cores e Variáveis

```css
--primary-color: #2c5aa0      /* Azul profissional */
--secondary-color: #e8f4f8    /* Azul claro */
--accent-color: #ff6b9d       /* Rosa/destaque */
--text-color: #333333         /* Cinza escuro */
--background-light: #f8f9fa   /* Fundo claro */
```

## 📱 Responsividade

O design é totalmente responsivo e se adapta para:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (abaixo de 768px)

## 🚀 Como Usar

1. **Adicione as imagens:**
   - Coloque a imagem principal em `image/photo/hero.jpg`
   - Coloque a foto da dra em `image/photo/dra-marina.jpg`
   - Adicione um favicon em `image/favicon/`

2. **Personalize o conteúdo:**
   - Edite os textos em `index.html`
   - Atualize os dados de contato
   - Modifique o nome da clínica

3. **Customize as cores:**
   - Altere as variáveis CSS em `css/global.css`
   - Mantenha a harmonia visual

4. **Adicione funcionalidades:**
   - Integre um sistema de agendamento
   - Configure o formulário de contato
   - Conecte links de redes sociais

## 💡 Dicas de Melhoria

- [ ] Adicionar animações ao scroll
- [ ] Implementar texto automatico ao clicar em agendar e ir ao WhatsApp
- [ ] Adicionar mais depoimentos com fotos
- [ ] Adicionar blog com dicas de skincare
- [ ] Adicionar certificados e prêmios
- [ ] Criar galeria de antes e depois

## 🔧 Tecnologias

- HTML5 semântico
- CSS3 com variáveis customizáveis
- Design Responsivo
- Mobile-First

## 📄 Licença

Este template é livre para usar e modificar conforme necessário.

---


