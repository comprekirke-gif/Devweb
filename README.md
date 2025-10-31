# Dev Solutions - Site de Divulgação de Serviços

Um site moderno e responsivo para divulgação de serviços de criação de sites, desenvolvido com HTML, CSS e JavaScript puro.

## 📋 Características

- **Banner Carrossel Automático**: 4 slides com transições suaves
- **Design Moderno**: Paleta de cores profissional (Preto, Branco, Roxo e Azul)
- **Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Seções Principais**:
  - Navbar fixa com navegação suave
  - Banner carrossel com controles manuais
  - Seção de Serviços (6 cards)
  - Seção de Benefícios (6 itens)
  - Seção de Preços (2 planos)
  - Seção de Contato
  - Footer com links sociais
  - Botão flutuante WhatsApp

## 🎨 Paleta de Cores

- **Preto**: `#0a0e27` - Cor principal de fundo
- **Branco**: `#ffffff` - Cor de texto principal
- **Roxo**: `#7c3aed` - Cor de destaque primária
- **Azul**: `#3b82f6` - Cor de destaque secundária

## 📦 Estrutura de Arquivos

```
website-service/
├── index.html          # Arquivo HTML principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidades JavaScript
└── README.md           # Este arquivo
```

## 🚀 Como Usar

### 1. Extrair os Arquivos
Descompacte o arquivo ZIP em seu computador.

### 2. Abrir o Site
Abra o arquivo `index.html` em seu navegador web:
- Clique duplo no arquivo `index.html`, ou
- Arraste o arquivo para o navegador, ou
- Use um servidor local (recomendado para melhor performance)

### 3. Usar um Servidor Local (Recomendado)

#### Com Python 3:
```bash
cd website-service
python -m http.server 8000
```
Depois acesse: `http://localhost:8000`

#### Com Node.js:
```bash
cd website-service
npx http-server
```

#### Com PHP:
```bash
cd website-service
php -S localhost:8000
```

## 🔧 Personalizações

### Alterar Telefone WhatsApp
Procure por `21982684928` nos arquivos e substitua pelo seu número:
- Formato: `+55` + DDD + número (sem caracteres especiais)

### Alterar Cores
No arquivo `styles.css`, modifique as variáveis CSS:
```css
:root {
    --cor-preto: #0a0e27;
    --cor-branco: #ffffff;
    --cor-roxo: #7c3aed;
    --cor-azul: #3b82f6;
}
```

### Alterar Preços
No arquivo `index.html`, procure pela seção `<!-- Seção de Preços -->` e modifique os valores:
- Site Profissional: `R$ 299,90`
- Site + Blog: `R$ 459,90`

### Alterar Textos
Todos os textos podem ser editados diretamente no arquivo `index.html`.

## 📱 Responsividade

O site é totalmente responsivo com breakpoints em:
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: até 480px

## ⚡ Funcionalidades JavaScript

- **Carrossel Automático**: Muda de slide a cada 5 segundos
- **Navegação Suave**: Scroll suave ao clicar em links
- **Animações ao Scroll**: Cards aparecem com animação ao entrar na viewport
- **Navbar Dinâmica**: Efeito de sombra ao scroll
- **Botão WhatsApp Flutuante**: Sempre visível com animação de bounce

## 🔗 Links Importantes

- **WhatsApp**: Integrado em todos os botões de ação
- **Redes Sociais**: Links no footer (customize conforme necessário)

## 📞 Informações de Contato

- **Telefone**: +55 21 98268-4928
- **Horário**: Segunda a Sexta, 9h às 18h
- **Localização**: Rio de Janeiro - RJ

## 💡 Dicas de Otimização

1. **Compressão de Imagens**: Se adicionar imagens, comprima-as antes
2. **Cache do Navegador**: Configure headers de cache para melhor performance
3. **CDN**: Considere usar um CDN para servir os arquivos
4. **Analytics**: Adicione Google Analytics para rastrear visitantes
5. **SEO**: Customize meta tags e adicione schema.org markup

## 🐛 Troubleshooting

### O carrossel não está funcionando
- Verifique se o arquivo `script.js` está no mesmo diretório
- Abra o console do navegador (F12) para verificar erros

### Botões WhatsApp não funcionam
- Verifique se o número está no formato correto: `+55DDNNNNNNNN`
- Certifique-se de que o link começa com `https://wa.me/`

### Estilos não aparecem
- Verifique se o arquivo `styles.css` está no mesmo diretório
- Limpe o cache do navegador (Ctrl+Shift+Delete)

## 📄 Licença

Este projeto é fornecido como está, livre para uso pessoal e comercial.

## 🤝 Suporte

Para dúvidas ou sugestões, entre em contato via WhatsApp: +55 21 98268-4928

---

**Desenvolvido com ❤️ por Dev Solutions**
