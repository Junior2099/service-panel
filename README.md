https://junior2099.github.io/service-panel/

# 🖨️ Painel Gráfica Rápida

Um painel moderno e intuitivo para gerenciar e acessar rapidamente ferramentas essenciais de uma gráfica rápida. Desenvolvido com HTML, CSS e JavaScript puro, oferece uma interface responsiva e personalizável.

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Usar](#como-usar)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Categorias de Ferramentas](#categorias-de-ferramentas)
- [Personalização](#personalização)
- [Recursos Adicionais](#recursos-adicionais)

## 🎯 Sobre o Projeto

O **Painel Gráfica Rápida** é uma aplicação web desenvolvida para centralizar e facilitar o acesso a diversas ferramentas online utilizadas em uma gráfica rápida. O painel oferece uma interface limpa e organizada, permitindo que os atendentes encontrem rapidamente as ferramentas necessárias para atender os clientes.

## ✨ Funcionalidades

### 🔍 Busca e Filtros
- **Busca em tempo real**: Pesquise ferramentas por nome ou categoria
- **Filtros por categoria**: Navegue entre Documentos, Imagens, Social, Financeiro e Outros
- **Atalho de teclado**: Use `Ctrl+K` (ou `Cmd+K` no Mac) para focar na busca

### 📊 Estatísticas
- **Contador de visitas**: Cada ferramenta registra quantas vezes foi acessada
- **Aba Mais Visitados**: Visualize as 6 ferramentas mais populares
- **Dados persistidos**: As estatísticas são salvas no navegador usando LocalStorage

### 🎨 Personalização
- **5 temas disponíveis**: Padrão, Azul, Verde, Rosa e Escuro
- **Preferências salvas**: O tema escolhido é salvo automaticamente
- **Interface responsiva**: Adapta-se perfeitamente a diferentes tamanhos de tela

### 📱 Responsividade
- **Desktop**: Layout completo com sidebar fixa
- **Tablet**: Sidebar adaptável com navegação horizontal
- **Mobile**: Interface otimizada para telas pequenas

### ⏰ Informações em Tempo Real
- **Relógio digital**: Hora atual atualizada a cada segundo
- **Data completa**: Exibição da data atual em português
- **Clima simulado**: Informações climáticas baseadas no horário do dia

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com variáveis CSS e Flexbox/Grid
- **JavaScript (Vanilla)**: Lógica da aplicação sem dependências externas
- **Font Awesome 6.4.0**: Ícones vetoriais
- **Google Fonts (Inter)**: Tipografia moderna
- **LocalStorage API**: Armazenamento local de dados

## 🚀 Como Usar

### Instalação

1. Clone ou baixe o repositório
2. Abra o arquivo `index.html` em um navegador moderno
3. Pronto! O painel está funcionando

### Uso Básico

1. **Buscar uma ferramenta**: Digite o nome da ferramenta na barra de busca
2. **Filtrar por categoria**: Clique em uma categoria na sidebar (Documentos, Imagens, etc.)
3. **Ver ferramentas populares**: Clique na aba "Mais Visitados"
4. **Acessar uma ferramenta**: Clique no botão "Acessar" no card da ferramenta
5. **Personalizar tema**: Clique em um dos círculos de tema na sidebar

## 📁 Estrutura do Projeto

```
.
├── index.html          # Arquivo principal (HTML, CSS e JavaScript)
└── README.md          # Documentação do projeto
```

## 📂 Categorias de Ferramentas

### 📄 Documentos (15 ferramentas)
- Juntar Documentos
- Resultados de Exames
- 2 via Contas
- Imprimir PDF
- Modelo de Currículo
- Cartão SUS
- Declaração de Residência
- Contrato de Locação
- Carta Convite
- Imprimir
- Cartão de Cadastro
- Editor de PDF
- Declaração de dependência
- Boletim de Ocorrência
- Autorização de Viagem

### 🖼️ Imagens (9 ferramentas)
- Remover Fundo
- Cortar Imagem
- Foto 3x4
- Tag 5x5
- Tag 4x4
- Melhorador de Fotos
- Fazer Texto
- Photopea
- Expandir Imagem (IA)
- Polaroid

### 💬 Social (1 ferramenta)
- WhatsApp Web

### 💰 Financeiro (1 ferramenta)
- Calculadora

### 🔧 Outros (1 ferramenta)
- Placas Casa Carne

**Total: 28 ferramentas**

## 🎨 Personalização

### Temas Disponíveis

1. **Padrão**: Verde musgo e verde escuro
2. **Azul**: Tons de azul profissional
3. **Verde**: Verde esmeralda vibrante
4. **Rosa**: Rosa e magenta
5. **Escuro**: Tema escuro para uso noturno

### Adicionar Nova Ferramenta

Para adicionar uma nova ferramenta, edite o array `tools` no JavaScript:

```javascript
{ 
    id: 29, 
    name: "Nome da Ferramenta", 
    url: "https://exemplo.com/", 
    icon: "fas fa-icon-name", 
    category: "document", 
    visits: 0 
}
```

**Categorias disponíveis:**
- `document` - Documentos
- `image` - Imagens
- `social` - Social
- `calculator` - Financeiro
- `other` - Outros

**Ícones disponíveis:** Use qualquer ícone do [Font Awesome](https://fontawesome.com/icons)

## 📱 Recursos Adicionais

### Atalhos de Teclado
- `Ctrl+K` / `Cmd+K`: Focar na barra de busca

### Armazenamento Local
- As preferências de tema são salvas automaticamente
- O contador de visitas persiste entre sessões
- Novas ferramentas adicionadas são mescladas com as existentes

### Compatibilidade
- ✅ Chrome/Edge (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

## 👥 Atendentes

Desenvolvido para uso pelos atendentes:
- **Heloiza**
- **Celiana**

## 📝 Notas

- O projeto não requer servidor ou build process
- Funciona completamente offline após o primeiro carregamento
- Os dados são armazenados apenas no navegador local
- Compatível com navegadores modernos (ES6+)

## 🔄 Atualizações Futuras

Possíveis melhorias:
- [ ] Exportar/importar configurações
- [ ] Modo escuro automático baseado no horário
- [ ] Mais temas personalizados
- [ ] Favoritos personalizados
- [ ] Histórico de acesso

## 📄 Licença

Este projeto é de uso interno para a Gráfica Rápida.

---

**Desenvolvido com ❤️ para facilitar o trabalho diário**

