# srv08 – openSUSE Leap 15

![openSUSE Leap 15, Git a Vagrant – virtuální laboratoř](./spos-vagrant.png)

Konfigurace vychází z `../Vagrant/Vagrantfile-opensuse`.

## Spuštění

```bash
vagrant up
vagrant ssh
```

## Ověření serveru

**Kontrolní kód:** `SPOS-3I-6585f0b2554a83a995d502a4401de77e8eb985ff323badcd73126e02358d57bd`

```text
Úloha: git-vagrant / SPOŠ / 3. I / v1
Distribuce: openSUSE Leap 15.6
Hostname: opensuse15
Kernel: 6.4.0-150600.23.73-default
Virtualizace: oracle
Čas UTC: 2026-11-12T19:14:52Z
Náhodné ID: c8d760ac-d3b3-409f-a4db-b6793b8b127f
```

## Obrázek

Vytvořeno vestavěným nástrojem `image_gen`. Použitý prompt je uložen v [přehledu promptů](../Images/server-prompts.json) pod názvem tohoto adresáře.
