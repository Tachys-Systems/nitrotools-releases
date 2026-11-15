# NitroTools — vydání

Instalační balíčky NitroTools (měřením řízené odlehčení Windows 10/11, Centrum + plugin pro Claude Code).
Zdrojový kód je soukromý; tady jsou jen artefakty vydání.

## Stažení
Nejnovější verze: [Releases → Latest](https://github.com/Tachys-Systems/nitrotools-releases/releases/latest) → `nitrotools-setup-X.Y.Z.exe`.
Instaluje se pro uživatele (bez práv správce) do `%USERPROFILE%\NitroTools`.

## Integrita
Každé vydání má `manifest-stable.json` (SHA-256 a velikost instalátoru) a `manifest-stable.json.sig`
— podpis ECDSA P-256 / SHA-256. Nainstalovaná verze ověří podpis i hash, než aktualizaci spustí.
Instalátor zatím není podepsaný Authenticode, takže SmartScreen může při prvním spuštění varovat.

---

# NitroTools — releases

Installers for NitroTools (measurement-driven Windows 10/11 slimming, Centrum app + Claude Code plugin).
Source is private; this repository only hosts release artifacts. Each release ships a signed
`manifest-stable.json` (+ `.sig`, ECDSA P-256) that installed copies verify before updating.
