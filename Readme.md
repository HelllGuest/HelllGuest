# 💻 Hello World, I'm Anoop Kumar (aka @helllguest)  
### *Digital Purist • Serial OS Reinstaller • Digital Hermit • Open-Source Evangelist*

I maintain my systems with the precision of a watchmaker and the ruthlessness of a Bond villain. When the slightest lag appears, I prescribe the only cure I trust: complete digital rebirth.

### **⚡ My Digital Lifestyle**
- **🔄 OS Reinstalls:** 3+ monthly (lag intolerance disorder)
- **🚰 Hydration:** Water-only (system coolant for humans)
- **🏋️ Fitness:** Gym by day, `rm -rf` by night
- **💤 Sleep:** "I'll just fix this one thing..." → sunrise

### **🔧 What I Can Do**  
- **📸 Photography** (I make pixels look pretty)  
- **🎬 Video Editing** (Premiere Pro > my social life)  
- **💻 Programming** (Python is my **holy grail**)  
- **🛠️ Computer Hardware Maintenance** (I fix what I break)  
- **🔒 Cybersecurity** (Protecting my digital kingdom) 

---

## **🛠️ The ThinkPad Trinity**
### **⚔️ Battle-Tested Machines**
| Model       | Storage               | RAM   | Multiboot Setup                  |
|-------------|-----------------------|-------|----------------------------------|
| **P15**     | 2x1.5TB NVMe (RAID 0) | 64GB  | Win11 + macOS + Arch (OpenCore)  |
| **T480**    | 2TB NVMe + SATA caddy | 32GB  | Win11 + macOS + Arch (OpenCore)  |
| **X1 Yoga** | 1TB NVMe (soldered)   | 16GB  | Win11 + macOS + Arch (OpenCore)  |

### **🧾 Reinstall Ritual**
1. **Early Warning System**
   ```bash
   # When systemd-analyze blame > coffee brew time
   if [ $(systemd-analyze blame | head -n1 | cut -d' ' -f2) -gt 500 ]; then
       echo "Initiating purge protocol..."
   fi
   ```

2. **Nuclear Sanitization**
   ```bash
   # For NVMe drives
   sudo blkdiscard /dev/nvme0n1
   # For stubborn sectors
   sudo dd if=/dev/zero of=/dev/sda bs=1M status=progress conv=fsync
   ```

3. **UEFI Baptism**
   ```bash
   # Cleanse the NVRAM
   sudo efibootmgr -B -b $(efibootmgr | grep 'Arch Linux' | cut -d' ' -f1 | tr -d '*Boot')
   ```

---

## **🏆 Reinstall Hall of Fame**
| Device  | OS          | Time   | Verification                  | Notes                          |
|---------|-------------|--------|-------------------------------|--------------------------------|
| P15     | Arch        | 4:37   | systemd-analyze output        | Pre-cached all packages        |
| T480    | Windows 11  | 6:12   | Task Manager screenshot       | Drivers on separate USB        |
| X1 Yoga | macOS       | 8:45   | OpenCore debug log            | SMBIOS memorized               |

*"Like F1 pit stops, but with more UEFI screaming"*

---

## **⚠️ Terms of Engagement**
**BY USING MY CODE, YOU AGREE TO:**

1. **ABSOVE ME WHEN:**
   - Your SSD develops PTSD
   - You miss life events due to installation loops
   - Your cat learns to say "kernel panic"
   - Your smart fridge starts tweeting conspiracy theories

2. **SWEAR TO:**
   - Keep backups in 3+ geological strata
   - Memorize `fsck` before complaining
   - Never ask "is this normal?" post-`rm -rf`
   - A backup personality (for when tech breaks you)

3. **ACCEPT THAT:**
   > "All systems are born clean and deserve to die clean"  
   > "`pacman -Syu` is the leading cause of second marriages"  
   > "If you're not reinstalling, you're accumulating sin"

4. **UNDERSTAND** that:  
   - This software comes with **NO WARRANTY**  
   - "It works on my machine" is a valid excuse  
   - If you break it, you get to keep both pieces  

*"With great open-source comes great responsibility... that I definitely don't have."*  

---

## **🔥 Fun Facts**  
- I once SSH'd into my own laptop... from my own laptop  
- My ThinkPads have **names and birthdays**  
- I consider `rm -rf /` a motivational quote  
- My ideal date is with `vim` and **no escape key**  

---

## **🌋 Current Experiments**
- **Project Phoenix:** OS that auto-reinstalls weekly
- **`install-fu`:** CLI tool that judges your life choices
- **SSD Valhalla:** Proper rites for worn-out storage

---

## **📫 Where to Find Me**
- **GitHub:** [@helllguest](https://github.com/helllguest) *(Commit history = reinstall log)*
- **Twitter:** [@helllguest](https://twitter.com/helllguest) *(Mostly live-tweeting kernel panics)*
- **Email:** helllguest@pm.me *(Replies may be delayed by spontaneous reinstall)*

---

## **💀 Tales from the Trenches**
- My P15's NVMe drives greet me with "Again?" in SMART logs
- Can recite Windows 11 EULA Article 17b from memory
- My T480's BIOS has PTSD from Secure Boot toggling
- Consider `sudo rm -rf /` a form of digital meditation

**The Helllguest Mantra:**  
✔️ If it works → Black magic  
❌ If it breaks → Learning opportunity  
💥 If it explodes → Worth the story  

*(This README will self-destruct after 30 days - like all good installs.)* 🚀
