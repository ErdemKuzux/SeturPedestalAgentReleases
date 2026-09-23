# SeturPedestalAgentReleases

**Setur (Beckhoff) pedestal agent** — Velopack güncelleme feed'i. Burada yalnızca **derlenmiş binary** yayınlanır; kaynak kod private repoda kalır.

- Kurulum: son sürümün **`SeturPedestalAgent-win-Setup.exe`** dosyasını indirip çalıştırın.
- Agent kendini bu repodaki release'lerden günceller (açılıştan 15 sn sonra + saatlik kontrol).
- `updateinfo.json` → `minVersion`: bu sürümün **altındaki** agent'lar güncellemeyi **ZORUNLU** uygular (hemen + restart).
  Üstündekiler için güncelleme opsiyoneldir (bir sonraki kapanışta uygulanır).
- Marina bazlı politika (panelden) bu global değerin önüne geçer.

> Inovance agent'ının feed'i AYRIDIR: `ErdemKuzux/PedestalAgentReleases`. İkisi asla karıştırılmaz.
