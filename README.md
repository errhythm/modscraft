# modscraft
Who said I can not use Github for gaming? This repository is for my friends to sync my mods with my computer directly. 

You should pull this repository **directly into your Minecraft mods folder** so that it always stays up to date.

---

## 📥 First Time Setup (Windows)
1. Install [Git](https://git-scm.com/downloads) if you don’t have it.
2. Open PowerShell and run:
   ```powershell
   cd $env:APPDATA\.minecraft
   git clone https://github.com/errhythm/modscraft.git mods
    ```

> This will create the repo directly as your `.minecraft/mods` folder.

---

## 🔄 Updating Mods

To get the latest mods, open PowerShell and run:

```powershell
cd $env:APPDATA\.minecraft\mods
git pull
```

That’s it! The mods will always match the server.

---

## ⚠️ Notes

* Make sure you have **Forge or Fabric** installed (depending on server requirements).
* If you accidentally delete a mod, just run `git pull` again to restore it.

