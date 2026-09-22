Aggresive adalah salah satu behaviour character

Aggresive berarti character tersebut dalam keadaan ingin mengurangi [[HealthPoint]] [[PlayerCharacter]]

## Pola aggresive

Character yang sedang aggresive bisa memilih salah satu action berikut

### Watching

Watching berarti character sudah menyadari kehadiran player character dalam radiusnya
Character yang ada dalam keadaan watching bisa jadi akan berjalan mendekat ke arah player character tetapi menjaga jarak aman
Jarak aman adalah sejauh 1x [[Dash]] kurang sedikit. Jadi player character masih mungkin untuk [[Menyerang]]-nya
Dalam keadaan watching, suatu character [[Vulnerable]]

### Telegraphing

Telegraphing berarti character dalam keadaan memberikan aba-aba bagi player character bahwa dia akan [[Menyerang]]
Player bisa melihat dengan jelas telegraphing ini seperti character tersebut mengambil jeda sebelum [[Menyerang]]
Dalam keadaan telegraphing, suatu character [[Vulnerable]]
Player bisa mengambil momen ini untuk bisa menyerang character tersebut
Dan jika player character berhasil menyerang character ini, maka rencana serangannya dibatalkan

### Evading

Evading berarti character dalam keadaan menghindari [[PlayerCharacter]]
Menghindari berarti menjauhkan diri dari player character
Character masuk dalam keadaan evading bisa jadi didasarkan pada jaraknya dengan player character
Dalam keadaan evading, suatu character [[Vulnerable]]
Ketika player character ada dalam radiusnya, maka character akan membuat keputusan apakah dia akan evading, defend, atau melakukan action lain
Tiap [[EnemyBot]] memiliki chance yang berbeda dalam membuat keputusan evading
Ada enemy yang memiliki kemungkinan lebih besar untuk evading, ada juga character yang lebih kecil kemungkinan untuk evade

### Defending

Defending berarti character dalam keadaan menahan [[Menyerang|serangan]] dari [[PlayerCharacter]]
Character yang sedang defending berarti dia [[Invulnerable]]

### Attacking

Attacking berarti character dalam keadaan melakukan serangan terhadap [[PlayerCharacter]]
Character yang sedang menyerang, akan [[Invulnerable]]
