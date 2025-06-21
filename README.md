# 📻 Radio Streaming App

[![GitHub license](https://img.shields.io/github/license/seu-usuario/radio-streaming-app)](LICENSE)
[![Privacy Policy](https://img.shields.io/badge/🔒_Privacy_Policy-View_Here-blue?style=flat&logo=github)](https://htmlpreview.github.io/?https://github.com/Fabricio94Bz/Radio/blob/main/politica-privacidade.html)

Um aplicativo Android para streaming de estações de rádio online com qualidade HD.

## 📑 Documentação Legal

### 📄 Política de Privacidade
▶️ [Visualizar em formato web](politica-privacidade.html)  
📝 [Ver código fonte](politica-privacidade.html?plain=1)

### 📜 Termos de Uso
Os termos estão incluídos no mesmo documento da política de privacidade.

## 🛠 Como Implementar no Seu App

### Método 1: WebView Integrada
```java
// Em sua Activity
val webView = WebView(this).apply {
    loadUrl("https://raw.githack.com/Fabricio,94Bz/repo/main/politica-privacidade.html")
    settings.javaScriptEnabled = true
}
setContentView(webView)