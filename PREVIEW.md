# Preview — How Many Tabs Do You Have Open?

- Bounty: [u-danu-how-many-tabs-do-you-have-open-d86e783d](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d) — Growth, $5 pot (1st $1.54, top 10 paid), free entry
- Deadline: 2026-11-26T21:55:00Z (27 Nov 04:55 WIB)
- Entry: the single number **1** — one tab open, this page. The far-low surprise: the field will send hoarder numbers, but size for its own sake does not count; 1 is the most believable count in the field and the only honest far-low answer (0 would be a lie — you submit from a browser tab).
- Program: `main.py`, pure Python stdlib, writes exactly 1 byte (`1`, no newline) to `/output/entry.txt`
- Repo: https://github.com/mihawnk-nft/u-danu-how-many-tabs-do-you-have-open-d86e783d

## Status

- [x] Kit downloaded, RULES.txt + competition.yaml read
- [x] Number chosen: 1 (judge-model simulation run but uninformative — every call picked Entry A, margin 3, all games 0.50; position bias on bare numbers. Choice rests on the published criteria, documented in README.md)
- [x] `main.py` written and tested locally (gate: exactly 1 UTF-8 char, not whitespace; output verified: `1`, 1 byte, no newline)
- [x] Repo created and pushed (public, MIT, 3 make.fun badges, About: homepage make.fun + topic makefun)
- [x] `makefun check` run 24 Nov ~06:03 WIB (dengan tar kosong sementara karena bundle belum bisa dibuat): **4 passed** (competition_open, snapshot 4 files / 8.839 bytes, license_osi MIT, entrypoint main.py → python3.13); **1 failed — transcripts_present** (bundle belum ada, lihat bawah); 2 skipped; 5 checks deferred to submission (repo_public, repo_owner, repo_created_after_open, commit_in_repo, duplicate_snapshot — semuanya sudah terpenuhi di sisi repo: public, dibuat 22:57:46Z setelah buka 21:56:15Z, commit sudah push)
- [ ] Transcripts bundle: TIDAK BISA diselesaikan di dalam run ini — `bundle --dry-run` menemukan 18 sesi Muse app tapi melaporkan **0 usage rows**; usage rows baru ditulis saat pesan run ini ter-deliver. Agen top-level harus, setelah run ini selesai: jalankan SELECT muse.db untuk usage rows (subagent ini id 505245c0-27b4-4420-857e-90743c724892 + parent agent id), lalu `bundle --repo <dev> --muse-app-dir ~/agents --out transcripts.tar.gz`, lalu `check` lagi. (Sama seperti kasus u-puan.)
- [ ] NOT submitted — submit only on the user's explicit green light
