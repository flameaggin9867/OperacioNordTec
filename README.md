# Operació Nord Tec

* **Autor:** Daniel Infante
* **Grup classe:** ASIX 1A

---

## Índex
- [Operació Nord Tec](#operació-nord-tec)
  - [Índex](#índex)
  - [Estat del projecte](#estat-del-projecte)
  - [Arquitectura de xarxa](#arquitectura-de-xarxa)
  - [Configuracions](#configuracions)
  - [Incidències i solucions](#incidències-i-solucions)
    - [Incidència 1: Autenticació a GitHub](#incidència-1-autenticació-a-github)
  - [Decisions tècniques](#decisions-tècniques)
  - [Reflexions tècniques](#reflexions-tècniques)

---

## Estat del projecte
* **Fet:** Inicialització del repositori Git i connexió amb GitHub.
* **Pendent:** Desenvolupament de la configuració de xarxa i documentació addicional.

---

## Arquitectura de xarxa
* **Topologia:** *
* * **IPs rellevants:** 
  * `IP Principal`:

---

## Configuracions
* Fitxers de configuració principals del projecte i la seva funció:
  * *(Exemple: fitxer de xarxa / serveis)*

---

## Incidències i solucions

### Incidència 1: Autenticació a GitHub
* **Missatge d'error:** `remote: Invalid username or token. Password authentication is not supported...`[cite: 2]
* **Quan:** Fase de `git push` cap al repositori remot.[cite: 2]
* **Causa:** GitHub no permet l'ús de contrasenyes tradicionals per seguretat; requereix un Token d'Accés Personal (PAT)[cite: 2].
* **Solució:** Generació d'un token clàssic a GitHub i ús com a contrasenya a la terminal.
* **Detectada per:** @flame986

---

## Decisions tècniques
* **Eina de control de versions:** Git / GitHub per la seva standardització i integració.
* **Alternatives:** Altres plataformes com GitLab (descartada per requisits del projecte).

---

## Reflexions tècniques
* Importància de gestionar correctament les credencials de seguretat (tokens) en entorns de desenvolupament.
* Valor d'una bona estructuració inicial del repositori per mantenir l'ordre.
