## **Estil de Codi**

- **Indentació:** Utilitza 4 espais per a la indentació. No facis servir tabuladors.
- **Línia màxima:** Limita la llargada de cada línia a 80-100 caràcters.
- **Comentaris:** Escriu comentaris clars i útils.


## **Issues**

### **1.1. Quan Reportar una Issue**
- Quan detectis un error (bug).
- Quan necessitis una funcionalitat nova (*feature request*).
- Quan vulguis documentar alguna millora o suggeriment.

### **1.2. Passos per Reportar una Issue**
1. **Obrir el Repositori**  
   Accedeix al repositori corresponent a GitHub.

2. **Anar a la Pestaña "Issues"**  
   Clica a la pestanya **Issues** que trobaràs al menú del repositori.

3. **Crear una Nova Issue**  
   Clica el botó **New Issue**.

4. **Completar el Formulari**  
   - **Títol**: Escriu un títol clar i concís.
   - **Descripció**: Inclou:
     - Una descripció del problema o suggeriment.
     - Passos per reproduir el problema (si és un bug).
     - El resultat esperat versus el resultat real.
     - (Opcional) Captures de pantalla o exemples de codi.
   - **Etiquetes (Labels)**: Si tens permisos, assigna etiquetes adequades com ara `bug`, `enhancement`, etc.

5. **Enviar la Issue**  
   Fes clic a **Submit new issue**.


## **Pull Requests**

### **Què és una Pull Request (PR)?**
Una Pull Request és una sol·licitud per fusionar els canvis d'una branca a una altra, normalment de la teva branca a la branca principal (*main* o *master*).

### **Passos per Crear una Pull Request**
1. **Crear una Branca**  
   Assegura't que treballes en una branca nova:
   ```bash
   git checkout -b nom-de-la-branca