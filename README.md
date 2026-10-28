# Grup Bulucu — Group Finder (Firefox)

**[Türkçe](#türkçe) · [English](#english)**

---

## Türkçe

Destek ekibinin Backoffice öğrenci sayfasında kullandığı iç araç: uygun grupları, 1-1 tutor slotlarını ve PL pencerelerini bulur; transfer, kayıt ve request işlerini kolaylaştırır.

### Kurulum
1. **[Kurulum sayfasını](https://batuhaann22.github.io/grup-bulucu-firefox/)** Firefox'ta açın ve **Firefox'a ekle**'ye tıklayın.
2. Firefox "bu siteye izin ver" diye sorarsa **Devam et / İzin ver**, sonra **Ekle**.
3. Dosya indiyse: Firefox penceresine sürükleyin ya da `about:addons` → ⚙ → **Dosyadan eklenti yükle**.

Firefox 128 veya üstü gerekir. Chrome kullanıyorsanız: **[Chrome Web Store](https://chromewebstore.google.com/detail/fjpekppnpjklbolbafnloifbdlkkmfam)**.

### Güncellemeler
Otomatik. Firefox günde bir kez `updates.json` dosyasına bakar ve yeni sürümü kendisi kurar. Hemen almak için: `about:addons` → ⚙ → **Güncellemeleri denetle**.

### İlk ayar
Eklenti simgesine tıklayın → **Settings**: dil, bölge (şube), saat dilimi → **Save** → Backoffice sayfasını yenileyin.

### Gizlilik
Eklenti yalnızca kullanıcının kendi Backoffice oturumuyla çalışır. Veriler sadece tarayıcıda gösterilir; geliştiriciye ya da üçüncü bir tarafa gönderilmez. Backoffice'e yalnızca kullanıcı bir işlemi onayladığında yazar.

### Bu depoda
| Dosya | Ne işe yarar |
|---|---|
| `index.html` | Kurulum sayfası (TR / EN) |
| `updates.json` | Firefox'un otomatik güncelleme için okuduğu dosya |
| `grup-bulucu-firefox-<sürüm>.xpi` | Mozilla tarafından imzalanmış eklenti paketleri |

---

## English

An internal tool for a support team, used on the Backoffice student page: finds suitable groups, 1-1 tutor slots and PL windows, and makes transfers, enrolments and requests easier.

### Install
1. Open the **[install page](https://batuhaann22.github.io/grup-bulucu-firefox/)** in Firefox and click **Add to Firefox**.
2. If Firefox asks to allow the site, choose **Continue / Allow**, then **Add**.
3. If the file was downloaded instead: drag it onto a Firefox window, or open `about:addons` → ⚙ → **Install Add-on From File**.

Requires Firefox 128 or later. On Chrome: **[Chrome Web Store](https://chromewebstore.google.com/detail/fjpekppnpjklbolbafnloifbdlkkmfam)**.

### Updates
Automatic. Firefox checks `updates.json` about once a day and installs new versions itself. To get one right away: `about:addons` → ⚙ → **Check for Updates**.

### First-time setup
Click the extension icon → **Settings**: language, region (branch), time zone → **Save** → reload the Backoffice page.

### Privacy
The extension works only with the user's own Backoffice session. Data is only displayed in the browser and is never sent to the developer or any third party. It writes to Backoffice only when the user confirms an action.

### In this repository
| File | Purpose |
|---|---|
| `index.html` | Install page (TR / EN) |
| `updates.json` | Read by Firefox for automatic updates |
| `grup-bulucu-firefox-<version>.xpi` | Extension packages signed by Mozilla |
