# srv07 – Ubuntu 24.04 LTS

![Ubuntu 24.04 LTS, Git a Vagrant – virtuální laboratoř](./spos-vagrant.png)

Konfigurace vychází z `../Vagrant/Vagrantfile-ubuntu`.

## Spuštění

```bash
vagrant up
vagrant ssh
```

## Ověření serveru

Skript `../overeni-serveru.sh` byl spuštěn uvnitř VM příkazem:

```bash
vagrant ssh -c "bash -s" < ../overeni-serveru.sh
```

**Kontrolní kód:** `SPOS-3I-bd2ee7e39aa46d7831b1d6e96dc83e73402cd6cd782963f7e16a3e2938cdd3f8`

```text
Úloha: git-vagrant / SPOŠ / 3. I / v1
Distribuce: Ubuntu 24.04.3 LTS
Hostname: ubuntu24
Kernel: 6.8.0-86-generic
Virtualizace: oracle
Čas UTC: 2026-11-12T17:55:00Z
Náhodné ID: ef24413e-1252-4d65-bb1c-e1edf0567d8c
```

Kód i záznam si ponechte spolu. Nové spuštění vytvoří nový kód.

## Obrázek

Vytvořeno vestavěným nástrojem `image_gen`. Použitý prompt je uložen v [přehledu promptů](../Images/server-prompts.json) pod názvem tohoto adresáře.
