# Clone do Layout - Prescrição Eletrônica CFM

## 📋 Descrição
Este é um clone **apenas do layout visual** do site de Prescrição Eletrônica do CFM (Conselho Federal de Medicina). 

**IMPORTANTE:** Todos os dados exibidos são **totalmente fictícios** e foram criados apenas para fins de teste de interface e segurança.

## 📁 Estrutura de Arquivos
```
cfm_clone/
├── index.html              # Página principal (HTML puro)
├── favicon.ico             # Ícone do navegador
├── README.md               # Este arquivo
├── content/
│   ├── css/
│   │   └── loading.css     # Estilos de carregamento
│   └── img/
│       └── icp.png         # Logo do ICP-Brasil
```

## 🚀 Como Usar

### Opção 1: Abrir Localmente
```bash
# Simplesmente abra o arquivo index.html em um navegador
open index.html
# ou
firefox index.html
# ou
chrome index.html
```

### Opção 2: Servir com Python
```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Depois acesse: `http://localhost:8000`

### Opção 3: Servir com Node.js
```bash
npx http-server
```

## 🔒 Dados Fictícios Utilizados
- **Médico:** Dr. Carlos Alberto Silva (CRM 12345 - SP)
- **Paciente:** João da Silva Santos (35 anos)
- **Código de Validação:** CFMP-AT-TESTE1234
- **Data:** 15/06/2026

## ⚠️ Avisos Legais
- Este é um clone **não-oficial** criado apenas para fins educacionais e de teste.
- Não é afiliado ao CFM ou ao Conselho Federal de Medicina.
- Não deve ser utilizado para fins fraudulentos ou ilegais.
- Todos os dados são fictícios e não representam pessoas reais.

## 🛡️ Testes de Segurança
Este clone pode ser utilizado para:
- ✅ Testar defesas contra clonagem de sites
- ✅ Validar proteções de honeypot
- ✅ Avaliar detecção de bots
- ✅ Testar WAF (Web Application Firewall)
- ✅ Análise de segurança de interface

## 📝 Notas Técnicas
- HTML puro (sem dependências externas)
- CSS inline para fácil portabilidade
- Responsivo (funciona em mobile e desktop)
- Sem chamadas de API (totalmente estático)

---
**Criado em:** 05/06/2026
**Versão:** 1.0
