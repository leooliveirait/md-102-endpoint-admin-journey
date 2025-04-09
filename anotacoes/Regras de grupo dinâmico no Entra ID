
🟩 **📌 Grupo Dinâmico – O que é?**  
- Tipo de grupo que **adiciona ou remove membros automaticamente** com base em **atributos** (como departamento, cargo, UPN etc).  
- Evita adicionar usuário manualmente = **mais eficiência** 🚀  
- Pode ser **de usuários** ou **de dispositivos** (atenção pra isso!).

---

🟩 **🧠 Conceitos-Chave:**

✔️ **Expressões de Regra**:  
- Usa **sintaxe específica**, tipo lógica de programação.  
- Ex: `(user.department -eq "TI")` → pega todo mundo do depto de TI.  

✔️ **Prefixos**:  
- `user.` → regras para usuários  
- `device.` → regras para dispositivos  
  > 🔥 **DICA de MEMÓRIA:** "Usuário é a estrela, começa com 'user', dispositivo é só suporte, vai de 'device'" 😄  

✔️ **Atributos Comuns** (gravar esses!):  
- `user.department`  
- `user.jobTitle`  
- `user.country`  
- `device.deviceOSType`  
- `device.trustType`

---

🟩 **📐 Exemplo de Sintaxe:**

```plaintext
(user.department -eq "Financeiro")
(user.jobTitle -contains "Gerente")
(device.deviceOSType -eq "Windows")
```

🚨 DICA:  
- `-eq` → igual  
- `-ne` → diferente  
- `-contains` → contém (tipo palavra-chave)  
- `-startsWith` e `-endsWith` → cuidado com maiúsculas/minúsculas!

---

🟩 **⚠️ Regras Importantes de Prova e Prática:**

🔹 **Só pode ter uma regra por grupo dinâmico**.  
   > Não dá pra empilhar várias regras tipo "se for de TI ou de RH".  
   > Nesse caso, usa operador lógico: `-or`  

🔹 **Grupos não podem ser "misto" (usuário + dispositivo)**  
   > Tem que escolher um ou outro no momento da criação.

🔹 **Para aplicar regra a grupos aninhados = não funciona!**  
   > Grupos dinâmicos **não avaliam membros de outros grupos**. Cada regra é **auto contida**.

🔹 **A atualização não é imediata**  
   > Pode levar alguns minutos até que os membros sejam ajustados após mudanças no atributo.

---

🟩 **🎯 Foco para Avaliação (MD-102)**:

✅ Saber interpretar uma expressão de regra  
✅ Saber **criar uma regra simples** com base em um cenário  
✅ Entender as **limitações** (grupo aninhado, regra única, tipo de membro)  
✅ Saber que as regras usam **atributos do Entra ID** (não do local AD puro)

---
