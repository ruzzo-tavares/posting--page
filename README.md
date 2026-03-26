# RoximBook 

**Post-Tester** tem como objetivo alcançar a conclusão da trilha 2 do curso HTML, CSS e JAVASCRIPT - Devstart(LAB365);  
Trata-se de uma **landing page moderna** que simula rede social com **formulário dinâmico**, **consumo de API real** (`jsonplaceholder.typicode.com`) e **design glassmorphism** inspirado em Flutter (Essa não foi uma exigência do comando do curso, porém foi uma escolha pessoal).  

## 🎯 **Funcionalidades**  
  
- ✅ **Form dinâmico** com validação (título + textarea);  
- ✅ **POST real** para JSONPlaceholder API (`fetch` + `JSON.stringify`);  
- ✅ **GET inicial** carrega 10 posts reais da API;  
- ✅ **Lista responsiva** com 5 posts visíveis + scroll;  
- ✅ **Glassmorphism** (backdrop-filter + transparência);  
- ✅ **Loading states** + feedback visual;  
- ✅ **100% responsivo** (mobile-first);  
- ✅ **Semântica HTML5** (`nav`, `main`, `section`, `article`);  
- ✅ **Fallback offline** (simula API local).  
  
## 🏗️ **Estrutura do Projeto**  
  
```plaintext  
roximbook/  
│  
├── index.html          # HTML + CSS inline + JS  
│  
└── assets/             # Assets necessários  
    └── fundo-page.png  # Imagem de fundo  
```  
  
## 🎨 **Design System**  
  
| Variável | Cor | Hex |  
|----------|-----|-----|  
| `--primary` | Principal | `#6750A4` |  
| `--accent` | Destaque | `#03DAC6` |  
| `--card` | Cards | `#25106a` |  
| `--glass` | Vidro | `rgba(255,255,255,0.6)` |  
  
## 🚀 **Como Usar**  
  
```bash  
# 1. Clone o projeto  
git clone https://github.com/ruzzo-tavares/posting--page.git  
cd posting--page  
  
# 2. Adicione sua imagem em assets/  
# 3. Abra index.html  
```  
  
## 📐 **Tecnologias**  
  
| Frontend | Features |  
|----------|----------|  
| **HTML5** | Semântica completa + ARIA |  
| **CSS3** | Glassmorphism, Grid, Flexbox, Backdrop-filter |  
| **JavaScript ES6+** | `async/await`, `fetch`, DOM manipulation |  
  
## 🔧 **API Integrada**  
  
```  
✅ GET  https://jsonplaceholder.typicode.com/posts?_limit=10  
✅ POST https://jsonplaceholder.typicode.com/posts  
📤 { title, body, userId: 1 }  
📥 { id, title, body, userId }  
```  
  
## 📋 **Fluxo Completo**  
  
```  
1. Carrega 10 posts que já estão na API utilizada  
2. Usuario digita título + conteúdo  
3. POST → API → Response  
4. Novo post no topo  
5. Limpa formulario e traz o feedback visual  
6. Fallback se API estiver offline  
```  
  
## 🎮 **Interações**  
    
- **Hover** botões (scale + shadow)  
- **Focus** inputs (border + glow)  
- **Loading** states (3 estados)  
- **Scroll suave** global  
- **Responsive** breakpoints (768px, 480px)  
  
### **Trocar Fundo**  
```css  
--bg-image: url("sua-imagem.jpg");  
```  
  
### **Nova Paleta**  
```css  
--primary: #nova-cor;  
--accent: #destaque;  
--card: #novo-fundo;  
```  
  
## 📄 **Licença**  
  
MIT-LICENSE  
  
## 👥 **Autor**  
  
**Ruzo Ts**    
🧑🏾‍💻 [GitHub](https://github.com/ruzzo-tavares) | 💻 Boa Vista, Roraima, BR  
  
***  