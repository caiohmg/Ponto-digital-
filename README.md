# 🍽️ PontoDigital

**Sistema de controle de ponto eletrônico para restaurantes** — PWA instalável no iPhone e Android, sem App Store.

## ✨ Funcionalidades

- 📷 **Leitura de QR Code** via câmera (API nativa BarcodeDetector)
- 🪪 **Reconhecimento facial** simulado com câmera frontal
- 👤 **Dois níveis de acesso**: Funcionário e Admin
- ➕ **Cadastro de funcionários** com captura de rosto
- 📊 **Painel admin** com estatísticas em tempo real
- 💾 **Dados persistidos** no dispositivo (localStorage)
- 📱 **PWA instalável** — funciona como app nativo no iPhone

## 📲 Instalar no iPhone

1. Abra `https://SEU-USUARIO.github.io/pontodigital` no **Safari**
1. Toque em **⬆️ Compartilhar**
1. Toque em **Adicionar à Tela de Início**
1. Toque em **Adicionar** ✅

## 🔐 Usuários padrão

|Nome               |Registro|Senha    |Tipo       |
|-------------------|--------|---------|-----------|
|Gerente Restaurante|00001   |admin123 |Admin      |
|João Silva         |00247   |joao123  |Funcionário|
|Maria Santos       |00312   |maria456 |Funcionário|
|Carlos Ferreira    |00089   |carlos789|Funcionário|

## 🛠 Tecnologia

- HTML/CSS/JS puro — arquivo único `index.html`
- `BarcodeDetector` API para leitura de QR Code
- `getUserMedia` para acesso à câmera
- Service Worker para funcionamento offline
- Sem dependências externas · 100% offline após primeiro carregamento

## 📋 QR Code do Balcão

Gere um QR Code com o texto abaixo e cole no balcão do restaurante:

```
RESTAURANTE:PONTO:BALCAO_PRINCIPAL
```

Qualquer gerador online gratuito funciona (ex: qr-code-generator.com).

## ⚠️ Requisitos

- **Câmera real**: necessário HTTPS (GitHub Pages já fornece)
- **QR Code**: Chrome 83+ / Edge 83+ (usa `BarcodeDetector`)
- **Instalação iOS**: obrigatório Safari

-----

*Desenvolvido como PWA — Progressive Web App*
