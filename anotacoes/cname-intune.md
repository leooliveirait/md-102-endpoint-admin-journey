
🟨 **📌 O que é o CNAME no contexto do Intune?**

- O **registro CNAME** é um tipo de entrada no **DNS público** do seu domínio personalizado.  
- Ele serve pra **facilitar o registro automático de dispositivos** no Intune, principalmente para **Windows**.

> 🧠 DICA: “O CNAME é tipo um atalho. O dispositivo tenta se registrar, e o CNAME aponta ele pro lugar certo!”

---

🟨 **🎯 Quando ele é necessário?**

✔️ **Registro automático no Intune para dispositivos Windows**  
✔️ Quando você está usando um **domínio personalizado** (tipo `empresa.com`)  
✔️ Principalmente útil em:
- **Hybrid Azure AD Join com auto MDM enrollment**
- **Azure AD Join com registro automático no Intune**

> 💡 **Microsoft.com e domínios padrões não precisam disso** (o DNS já está preparado)

---

🟨 **🛠️ Como configurar o CNAME?**

No **provedor de DNS** (GoDaddy, Registro.br, Cloudflare etc), crie:

| Tipo  | Nome                         | Valor                                               |
|-------|------------------------------|------------------------------------------------------|
| CNAME | `enterpriseenrollment`      | `enterpriseenrollment.manage.microsoft.com`         |
| CNAME | `enterpriseregistration`    | `enterpriseregistration.windows.net`               |

> 🔧 Às vezes só o primeiro já resolve pro Intune, mas o segundo é bom pra registro geral.

---

🟨 **⚠️ Pontos de atenção:**

🔹 Sem o CNAME, o Windows pode **não conseguir detectar automaticamente** o Intune como MDM.  
🔹 O usuário pode receber erro ao tentar registrar o dispositivo.  
🔹 Pode afetar o **registro silencioso** (tipo Autopilot ou Hybrid).

---

🟨 **📍Onde verificar se o CNAME tá funcionando?**

- Use o **dsregcmd /status** no Windows (linha de comando)  
  > Verifica estado de junção e MDM

- Ferramentas de verificação DNS (ex: nslookup, MXToolbox)

- Também aparece em **Intune Admin Center → Devices → Enroll devices → Automatic Enrollment**

---

🟨 **💡 Dica de prova:**

✅ Quando o problema for "registro automático não está funcionando", **verificar CNAME no DNS** é um dos primeiros passos.

✅ Se o domínio foi adicionado recentemente, **pode levar um tempo** até o CNAME propagar.

> 🧠 Frase pra lembrar:  
> “Sem CNAME, o dispositivo se perde no caminho.”

---
