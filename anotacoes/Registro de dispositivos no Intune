
🟦 **📌 O que é o Registro de Dispositivo?**

- É o **processo de conectar um dispositivo ao Intune** pra que ele possa ser **gerenciado remotamente**.  
- O Intune começa a aplicar **políticas, apps, compliance e proteção** só depois que o dispositivo está registrado.  
> 🧠 DICA: “Sem registro, sem controle!”

---

🟦 **🎯 Tipos de Registro (tem que saber esses!):**

1. **Windows Autopilot**
   - Ideal pra **provisionamento zero-touch**  
   - Já configura o Windows, junta no Entra ID, e registra no Intune  
   - Muito usado em **empresas com novos dispositivos**  
   > DICA: “Autopilot = piloto automático pra setup completo”

2. **Co-Management (com ConfigMgr)**
   - Dispositivo é gerenciado **tanto pelo Intune quanto pelo SCCM (ConfigMgr)**  
   - Ajuda quem está **migrando** pra nuvem

3. **Bring Your Own Device (BYOD)**
   - Dispositivo pessoal  
   - Usa o **portal de empresa** para registrar  
   - Modo: **"registro via aplicativo" (Intune Company Portal)**  
   - Aplica só políticas leves (MAM/Compliance)  
   > DICA: “Dispositivo pessoal, controle parcial”

4. **Azure AD Join + Intune**
   - Quando o dispositivo entra no **Azure AD**  
   - Registro automático se Intune está habilitado  
   - Muito comum com **Autopilot**

5. **Hybrid Azure AD Join + Intune**
   - Dispositivos do **AD local** também entram no Azure AD  
   - Registro é automático **com conector**  
   - Usado em **ambientes híbridos**

6. **Apple/Android Enrollment**
   - **iOS/iPadOS/Android** têm seus próprios métodos (usuário, Apple DEP, Android Work Profile etc)

---

🟦 **🛠️ Pré-requisitos para o Registro funcionar:**

✔️ **Licença Intune ativa pro usuário**  
✔️ **Permissão de registro atribuída no Entra ID**  
✔️ **Política de Registro configurada no Intune**  
✔️ DNS configurado se for híbrido  
✔️ O dispositivo tem que ter **conexão com a internet** no primeiro login

---

🟦 **📌 Onde configurar tudo isso?**

- **Microsoft Intune Admin Center** → Devices → Enroll devices  
- Ali ficam os métodos de registro e suas políticas

---

🟦 **⚠️ Pontos que caem em prova:**

✅ Saber identificar o método de registro ideal conforme o cenário  
✅ Entender **diferença entre Azure AD Join, Hybrid, BYOD e Autopilot**  
✅ Saber que o **registro = requisito pro gerenciamento**  
✅ Estar atento aos **pré-requisitos técnicos**  
✅ Entender a relação com **licenciamento do Intune e permissões no Entra ID**

---

🟦 **🧠 Dica pra lembrar os tipos (sigla maluca mas ajuda):**  
**"A CHA-WB"**  
- A → Autopilot  
- C → Co-management  
- H → Hybrid AAD Join  
- A → AAD Join direto  
- W → Work profile (Android)  
- B → BYOD  

---
