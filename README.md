# 🧼 SICRO – Sistema de Controle de Roupas

Aplicação web para controle de entrada, saída e solicitação de roupas estéreis, voltada ao setor da saúde.

## 🚀 Acesso Online


---

## 🩺 Destaques

- ✅ Voltado especialmente para o setor da saúde
- 🔍 Controle apurado por **lote**, **validade** e **categoria**
- 📦 Produção pode **solicitar e acompanhar** a separação das ordens em tempo real
- 🌐 Sistema **web, multiusuário**, acessível de qualquer dispositivo

---

## 🛠️ Tecnologias Utilizadas

- Python + Flask
- PostgreSQL
- HTML, CSS, JavaScript
- Jinja2 + Bootstrap

---

## ⚙️ Como rodar localmente

```bash
git clone https://github.com/lucasvrmoreira/SICRO
cd SICRO
python -m venv venv
source venv/bin/activate  # Linux/macOS
# ou
venv\Scripts\activate     # Windows

pip install -r requirements.txt

# Configure seu arquivo .env com a DATABASE_URL

python app.py
