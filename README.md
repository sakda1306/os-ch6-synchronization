# OS Chapter 6 — Process Synchronization (เว็บสรุปบทเรียน)

เว็บเรียน Operating System บทที่ 6 แบบทีละหัวข้อ เรียบเรียงจากสไลด์ *CH6 Process Synchronization* และหนังสือ *Operating System Concepts* 10th ed. (Silberschatz, Galvin, Gagne) บทที่ 6

## เนื้อหา
| # | บทเรียน | หนังสือ | สไลด์ |
|---|---|---|---|
| 00 | เริ่มที่นี่: วิธีเรียนบทนี้ | – | – |
| 01 | Background และ Race Condition | §6.1 | 6.3–6.6 |
| 02 | The Critical-Section Problem | §6.2 | 6.7–6.11 |
| 03 | Peterson's Solution | §6.3 | 6.12–6.14 |
| 04 | Hardware Support (Barrier, TAS, CAS, Atomic) | §6.4 | 6.15–6.21 |
| 05 | Mutex Locks และ Spinlock | §6.5 | 6.22–6.23 |
| 06 | Semaphores (มีตัวจำลอง) | §6.6 | 6.24–6.28 |
| 07 | Deadlock, Starvation, Priority Inversion | §6.8 | 6.29 |
| 08 | Classic Problems: Bounded-Buffer, Readers–Writers | บท 7 | 6.30–6.37 |
| 09 | Monitors และ Condition Variables | §6.7 | 6.39–6.44 |
| 10 | Evaluation | §6.9 | – |
| 11 | Synchronization ใน Solaris / Windows / Linux / Pthreads | บท 7 | 6.45–6.49 |
| 12 | สรุปก่อนสอบ + โจทย์ท้ายบทพร้อมแนวตอบ | §6.10 | – |
| 13 | แบบทดสอบ 12 ข้อ | – | – |

## เปิดบน GitHub Pages
Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save

## หมายเหตุ
รูปในโฟลเดอร์ `img/` ตัดมาจากหนังสือ Operating System Concepts เพื่อใช้ประกอบการศึกษาเท่านั้น ลิขสิทธิ์เป็นของผู้แต่งและสำนักพิมพ์ (Wiley)
