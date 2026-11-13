# srv03 – CentOS Stream 10

![CentOS Stream 10, Git a Vagrant – virtuální laboratoř](./spos-vagrant.png)

Konfigurace vychází z `../Vagrant/Vagrantfile-centos`.

## Spuštění

```bash
vagrant up
vagrant ssh
```

## Ověření serveru

**Kontrolní kód:** `SPOS-3I-c5cfd7a99882ad54e132edccda7359d496fb4a63e3e732a7d035b719715574e7`

```text
Úloha: git-vagrant / SPOŠ / 3. I / v1
Distribuce: CentOS Stream 10 (Coughlan)
Hostname: centos10
Kernel: 6.12.0-142.el10.x86_64
Virtualizace: oracle
Čas UTC: 2026-11-13T07:00:23Z
Náhodné ID: 3ea7e475-3850-4d6d-9c98-f766eafb6c40
```

## Obrázek

Vytvořeno vestavěným nástrojem `image_gen`. Použitý prompt je uložen v [přehledu promptů](../Images/server-prompts.json) pod názvem tohoto adresáře.
