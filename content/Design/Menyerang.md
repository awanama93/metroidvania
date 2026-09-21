Player bisa menyerang [[EnemyBot]] dengan menggunakan action berikut [[Dash]] dan semua action turunannya

Ketika dash mengenai enemy bot, maka [[HealthPoint]] Enemy bot akan berkurang minimal 1 dan maksimal 4

Dash akan menghasilkan damage pada enemy jika enemy sedang ada dalam state [[Vulnerable]]

Jika dash mengenai enemy yang sedang dalam keadaan [[Invulnerable]] maka damage tidak akan terjadi

## Damage

Berikut adalah daftar pemetaan efektivitas dash dalam menyerang [[EnemyBot]]:

| Action         | Damage deal |
| -------------- | ----------- |
| [[Dash]]       | 1           |
| [[DoubleDash]] | 2           |
| [[LongDash]]   | 2           |
| [[JumpDash]]   | 1           |
