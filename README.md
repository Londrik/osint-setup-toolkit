# 🛠️OSINT Setup & Investigation Toolkit

Repositório destinado à documentação e mapeamento de ferramentas e metodologias para investigações de fontes abertas (**OSINT - Open Source Intelligence**), validação de e-mails, rastreamento de presença digital e auditoria de vulnerabilidades públicas.

---

##  Ferramentas Mapeadas

### ✉️E-mail & Presença Digital
* **[Holehe](https://github.com/megadose/holehe):** Verifica se um e-mail está cadastrado em mais de 120 plataformas/serviços web via requisições passivas.
* **[h8mail](https://github.com/khast3x/h8mail):** Ferramenta para verificação de vazamento de credenciais e e-mails em bases públicas de Data Breaches.

###  Validação de Telefones
* **[Ignorant](https://github.com/megadose/ignorant):** Verifica se um número de telefone está registrado no WhatsApp e em outras redes.

###  Registros & Infraestrutura
* **WHOIS / Registro.br:** Consultas a diretórios estaduais/nacionais de domínios `.br` para identificação de titularidade jurídica e contatos técnicos.
* **cURL & Google Dorks:** Extração de cabeçalhos HTTP e operadores de busca avançada para indexação pública.

###  Relatórios & Documentação
* **ReportLab (Python):** Engine para geração automatizada de relatórios em formato PDF com matriz de riscos e evidências.

---

## ⚖️Conformidade e Amparo Legal

Todas as análises conduzidas utilizando estas ferramentas enquadram-se estritamente na coleta de dados públicos e ostensivos:
* **Sem transposição de barreiras:** Não envolve exploração de vulnerabilidades, acesso não autorizado ou invasão de dispositivo (conforme o Art. 154-A do Código Penal).
* **LGPD (Lei 13.709/2018):** Tratamento pautado no Legítimo Interesse para autoproteção/prevenção a fraudes (Art. 7º, IX) e uso de dados tornados manifestamente públicos pelo próprio titular (Art. 7º, § 4º).

---

## ⚙️Instalação Rápida no Linux

```bash
# Atualizar repositórios e instalar utilitários de sistema
sudo apt update && sudo apt install -y whois python3-pip

# Instalar ferramentas OSINT via PIP (escopo de usuário)
python3 -m pip install holehe ignorant h8mail reportlab --break-system-packages

