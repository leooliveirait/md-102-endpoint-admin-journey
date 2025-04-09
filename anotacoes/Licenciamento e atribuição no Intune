
🟧 **📌 Por que o Licenciamento é importante no Intune?**

- O **Intune só funciona** se o usuário (ou dispositivo, dependendo do cenário) **tiver uma licença compatível atribuída**.
- Sem licença = **nada de políticas, apps, compliance ou registro**.
> 🧠 DICA: "Sem licença, sem gerência!"

---

🟧 **🎯 Tipos de Licenças que dão direito ao Intune:**

✅ **Microsoft Intune (standalone)**  
✅ **Microsoft 365 E3 / E5**  
✅ **Microsoft 365 Business Premium**  
✅ **Enterprise Mobility + Security (EMS) E3 / E5**  
✅ **Microsoft 365 F1 / F3** (atenção: F1 tem restrições!)  

> 💡 Algumas dessas vêm com **outros serviços acoplados**, tipo Entra ID P1, Defender etc.

---

🟧 **📌 Como atribuir licença aos usuários?**

1. **Manual (via Entra ID)**  
   - Ir no usuário > "Licenças" > "+ Atribuir licenças"  
   - Desmarcar o que não precisa (pra evitar sobreposição)

2. **Atribuição via Grupo (Recomendado!)**  
   - Cria grupo (estático ou dinâmico) e vincula licença ao grupo  
   - Boa prática pra **escala e consistência**

---

🟧 **⚠️ Cuidados com Licenciamento e Prova:**

🔹 **Usuário precisa da licença ANTES de tentar registrar**  
🔹 **Licenças aplicadas por grupo são retroativas**, mas **demoram alguns minutos**  
🔹 **Apenas usuários com licenças atribuídas aparecem no Intune Admin Center**

> 🧠 Pegadinha: "Usuário sem licença aparece no Entra ID, mas não no Intune!"

---

🟧 **🔐 E sobre Dispositivos? Preciso de licença pra cada um?**

- O foco do licenciamento é **por usuário**, e não por dispositivo.
- Um usuário pode ter **até 15 dispositivos registrados** no Intune (por padrão).
- Exceção: cenários como **licenciamento por dispositivo compartilhado**, ex: **quiosques**.

---

🟧 **📍Onde vejo e gerencio isso tudo?**

- **Microsoft Entra ID** (ou Azure AD) → Atribuição de Licenças  
- **Microsoft 365 Admin Center** → Gerenciar assinaturas  
- **Microsoft Intune Admin Center** → Devices e Users, mas só mostra quem já tem licença

---

🟧 **💡 Dica de Prova:**

✅ Sempre conferir:
- Se o usuário tem **licença válida**
- Se está **atribuída diretamente ou por grupo**
- Se o grupo dinâmico está **pegando os membros certos**

> ⚠️ MUITAS QUESTÕES colocam o problema como “usuário não aparece no Intune” – e a resposta costuma ser: “licença não atribuída”.

---

🟧 **🧠 Frase pra lembrar:**
> “Licença é o passaporte do Intune. Sem ela, o usuário nem embarca.”

---
