# 📋 Aplicativo de Auditoria em Normas Regulamentadoras (NRs)

Este aplicativo tem como objetivo **facilitar auditorias técnicas baseadas nas Normas Regulamentadoras (NRs) do Ministério do Trabalho**, oferecendo uma interface prática e objetiva para preenchimento de não conformidades, evidências e planos de ação diretamente via dispositivos Android.

---

## ✅ Funcionalidades

- 📌 Checklist interativo baseado nas principais NRs (NR-01 a NR-37)
- 📝 Registro de evidências fotográficas e anotações por item auditado
- 📊 Geração de relatórios automatizados em PDF ou planilha
- 👥 Cadastro de auditores, empresas e áreas auditadas
- 🔒 Armazenamento seguro local ou em nuvem (opcional)
- 📤 Exportação de dados para análise e integração com sistemas de gestão

---

## ⚙️ Tecnologias Utilizadas

- **Plataforma**: MIT App Inventor / Kodular / Flutter (dependendo da versão)
- **Frontend**: HTML5, CSS3, JavaScript (para formulários)
- **Backend (opcional)**: Firebase / Google Sheets / SQLite
- **Compatibilidade**: Android 5.0 ou superior

---

## 📥 Instalação

### 🔹 Via APK (usuário final)

1. Baixe o arquivo `auditoria-nrs.apk`
2. Habilite **"Fontes desconhecidas"** nas configurações do seu celular
3. Instale e execute o aplicativo normalmente

### 🔹 Via MIT App Inventor (desenvolvedores)

1. Acesse: [https://ai2.appinventor.mit.edu](https://ai2.appinventor.mit.edu)
2. Importe o arquivo `.aia` do projeto
3. Edite os componentes conforme necessário
4. Compile em: `Build > App (.apk)`

---

## 🧪 Uso Básico

1. Abra o app e selecione a NR desejada (ex: NR-10 – Segurança em Instalações Elétricas)
2. Para cada item do checklist:
   - Marque como **conforme**, **não conforme**, ou **não se aplica**
   - Registre observações ou adicione fotos
3. Ao final, gere o relatório da auditoria
4. Envie por e-mail, salve localmente ou envie para o gestor responsável

---

## 📁 Estrutura de Arquivos

```bash
.
├── README.md
├── checklists/
│   ├── nr01.html
│   ├── nr10.html
│   └── ...
├── assets/
│   ├── logo.png
│   └── estilos.css
├── app/
│   └── auditoria-nrs.aia
└── dist/
    └── auditoria-nrs.apk
