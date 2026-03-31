# 🧪 QA Case Study – INIS Immigration Portal

## 📌 1. Introduction | Introdução

**EN:**
This project presents a real-world QA case study based on the Irish Immigration Portal (INIS).  
The objective was to identify inconsistencies between Desktop and Mobile platforms during the visa renewal process.

**PT:**
Este projeto apresenta um estudo de caso real de QA baseado no portal de imigração da Irlanda (INIS).  
O objetivo foi identificar inconsistências entre as plataformas Desktop e Mobile durante o processo de renovação de visto.

---

## 🎯 2. Objective | Objetivo

**EN:**
- Validate system behavior across different devices
- Identify inconsistencies in application status
- Document bugs and propose improvements

**PT:**
- Validar o comportamento do sistema em diferentes dispositivos
- Identificar inconsistências no status da aplicação
- Documentar bugs e propor melhorias

---

## 🌐 3. Scope | Escopo

**Tested features | Funcionalidades testadas:**
- Login system
- "My Forms" dashboard
- Additional Information submission
- Application status visualization

---

## 🧪 4. Test Environment | Ambiente de Teste

| Platform | Browser | Device |
|----------|--------|--------|
| Desktop  | Chrome | Windows |
| Desktop  | Edge   | Windows |
| Mobile   | Chrome | Android |

---

## 🧾 5. Test Scenarios | Cenários de Teste

| ID | Scenario | Description |
|----|---------|------------|
| TC001 | Login | User logs into the system |
| TC002 | View Forms | Access "My Forms" dashboard |
| TC003 | Submit Documents | Upload and submit documents |
| TC004 | Cross-platform Test | Compare Desktop vs Mobile behavior |

---

## 🐞 6. Bug Report | Relatório de Bug

### 🔴 Bug Title:
Inconsistent application status between Desktop and Mobile

### 📍 Environment:
- Desktop: Chrome (Windows)
- Mobile: Chrome (Android)

### 🔁 Steps to Reproduce:
1. Log in to the INIS portal
2. Navigate to "My Forms"
3. Check application status

### ✅ Expected Result:
The application status should be consistent across all devices

### ❌ Actual Result:
- Desktop shows: 0 forms submitted  
- Mobile shows: Application submitted  

### ⚠️ Severity:
High

### 🚨 Impact:
- User confusion about submission status  
- Risk of duplicate submissions  
- Potential delays in visa processing  

---

## 🧠 7. Analysis | Análise

**EN:**
The issue may be caused by synchronization failure between frontend and backend systems, or caching inconsistencies across devices.

**PT:**
O problema pode ser causado por falha de sincronização entre frontend e backend, ou inconsistência de cache entre dispositivos.

---

## 💡 8. Suggested Improvements | Sugestões de Melhoria

- Ensure real-time synchronization across platforms  
- Provide confirmation message after submission  
- Send automatic confirmation email  

---

## 📊 9. Results | Resultados

| Test Case | Result |
|----------|-------|
| TC001 | Pass |
| TC002 | Fail |
| TC003 | Pass |
| TC004 | Fail |

---

## 📚 10. Lessons Learned | Lições Aprendidas

**EN:**
- Cross-platform testing is essential  
- Clear feedback improves user experience  
- Real-world testing enhances QA skills  

**PT:**
- Testes multiplataforma são essenciais  
- Feedback claro melhora a experiência do usuário  
- Testes reais desenvolvem habilidades de QA  

---

## 🚀 11. Conclusion | Conclusão

**EN:**
This project demonstrates my ability to identify real-world issues, document bugs, and analyze their impact on users.

**PT:**
Este projeto demonstra minha capacidade de identificar problemas reais, documentar bugs e analisar seu impacto para o usuário.

---

## 📎 12. Attachments | Anexos

- Screenshots (in /screenshots folder)
- Test results spreadsheet# qa-analysis-irish-immigration-site
QA analysis of Irish Immigration website - usability, bugs and improvements
