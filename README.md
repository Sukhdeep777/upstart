# UPSTART Diagrama Gantt
```mermaid
gantt
    title Planificació del projecte UPSTART (4 Setmanes)
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m

    section Sprint 1: Pàgina
    Generar web :active, s1t1, 2026-05-05, 1d
    Estructura HTML, CSS i disseny     :s1t2, after s1t1, 4d

    section Sprint 2: Informe
    Documentar arquitectura i disseny  :s2t1, 2026-05-06, 2d
    Explicació codi i manual d'estil   :s2t2, 2026-05-08, 7d
    Especificació JS                   :s2t3, 2026-05-12, 4d

    section Sprint 3: Pàgina Detallada
    JavaScript      :s3t1, 2026-05-11, 2d
    Responsive i Comentaris            :s3t2, 2026-05-13, 3d

    section Sprint 4: Servidor
    RPi           :s4t1, 2026-05-18, 1d
    SV               :s4t2, 2026-05-25, 1d

    section Sprint 5: Implementar
    Desplegament i proves         :s5t1, 2026-05-18, 3d
    Configuració produc.             :crit, s5t2, 2026-05-21, 2d

    section Sprint 6: Revisió
    Testeig general             :crit, s6t1, 2026-05-25, 3d
    Prep. Entrega                 :crit, s6t2, 2026-05-28, 2d
```
# 📅 Planificació del Projecte: Servidor Raspberry Pi i Web

## 🏃 Sprint 1: Pàgina
**OBJECTIU:** Creació d'una pàgina simple per a la comprovació del funcionament i desplegament.

### Tasca 1 (Setmana 1) - Dilluns
- [ ] Generar la pàgina web inicial.
- [ ] Pujar la pàgina al **Github Pages** i **Vercel**.
- [ ] Crear totes les pàgines i començar amb l'estructura **HTML i CSS**.

### Tasca 2 (Setmana 1) - Dimarts a Divendres
- [ ] Estructurar la pàgina web per una nota mínima per aprovar.
- [ ] Implementar imatges i botons.
- [ ] Definir l'estructura final del lloc.

---

## 📝 Sprint 2: Informe
**OBJECTIU:** Creació de l'informe per documentar el projecte i els processos.

### Tasca 1 (Setmana 1) - Dimecres a Dijous
- [ ] Documentar l'arquitectura triada.
- [ ] Seleccionar el disseny inicial.

### Tasca 2 (Setmana 2) - Divendres a Dijous
- [ ] Explicació del codi.
- [ ] Manual d'estil de colors.
- [ ] Implementar descripció de les eines utilitzades.

### Tasca 3 (Setmana 2) - Dimarts a Divendres
- [ ] Especificar el JS per saber com programar les funcions.

---

## 💎 Sprint 3: Pàgina Detallada
**OBJECTIU:** Aplicar totes les funcions i millorar la pàgina professionalment.

### Tasca 1 (Setmana 2) - Dilluns a Dimarts
- [ ] Intentar implementar **Login** i una **Base de Dades**.
- [ ] Implementar interactivitat amb **JavaScript**.
- [ ] Planificació de plans.

### Tasca 2 (Setmana 2) - Dimecres a Divendres
- [ ] Implementar **Responsive Web Design**.
- [ ] Crear sistema d'entrades i comentaris per a usuaris.

---

## 🖥️ Sprint 4: Servidor
**OBJECTIU:** Creació d’un servidor en una Raspberry Pi.

- [ ] **Tasca 1 (Setmana 3):** Configuració inicial (Dilluns).
- [ ] **Tasca 2 (Setmana 4):** Ajustos del servidor (Dilluns).

---

## 🚀 Sprint 5: Implementar
**OBJECTIU:** Implementar la pàgina web en el servidor de la Raspberry.

- [ ] **Tasca 1 (Setmana 3: L-M-X):** Desplegament inicial i proves de xarxa.
- [ ] **Tasca 2 (Setmana 3: J-V):** Configuració final de producció.

---

## 🔍 Sprint 6: Revisió
**OBJECTIU:** Revisar tot el treball realitzat.

- [ ] **Tasca 1 (Setmana 4: L-M-X):** Testeig general i depuració de bugs.
- [ ] **Tasca 2 (Setmana 4: J-V):** Preparació de l'entrega final.
