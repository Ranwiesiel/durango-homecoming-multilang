# 05 — Status abnormal / efek

## Kredit / Sumber

- **Penyusun data asli:** [kghj76138](https://github.com/kghj76138) — repo [durango-homecoming-guide](https://github.com/kghj76138/durango-homecoming-guide)
- **Situs panduan:** [Durango:0 Buku Data Lapangan (Homecoming)](https://kghj76138.github.io/durango-homecoming-guide/)
- Paket ini adalah **terjemahan & penataan ulang** (Bahasa Indonesia) untuk dipakai bersama server private — **bukan** dokumen resmi Nexon
- Silakan tetap cantumkan kredit ke kghj76138 bila membagikan ulang

Total **371** · `csv/effects.csv`

| id | nama | maks | #eff | deskripsi |
|---|---|---:|---:|---|
| `clothes` | Pakaian dasar | 1 | 0 | Memakai pakaian: kelelahan tertahankan. |
| `accessory` | Kesesuaian iklim | 1 | 0 | Pakai perlengkapan sesuai iklim: kelelahan tertahankan. |
| `dirty` | Kotor | 1 | 1 | Tubuh kotor: kelelahan menumpuk. |
| `clean` | Mandi | 1 | 1 | Mandi: bersih, panas dan lelah tertahankan. |
| `wet` | Basah | 1 | 6 | Basah: suhu turun. Di panas lelah tertahankan, di dingin menumpuk. |
| `drink_water` | Air minum | 1 | 5 | Minum: haus hilang, kelelahan tertahankan. |
| `cactus_water` | Pembasah tenggorokan | 1 | 4 | Sari buah membasahi tenggorokan: kelelahan tertahankan.  |
| `fruit_water` | Sari buah | 1 | 2 | Banyak sari buah: kelelahan lebih tertahankan. |
| `thirsty` | Haus | 1 | 2 | Tenggorokan kering: kelelahan berat menumpuk. |
| `warm_up` | Api unggun | 1 | 4 | Kering dan hangat: di dingin lelah tertahankan, di panas menumpuk. |
| `observe_death` | Menyaksikan kematian | 1 | 1 | Menyaksikan kematian: kelelahan menumpuk. |
| `encouraged` | Disemangati | 1 | 1 | Disemangati: kelelahan tertahankan.  |
| `do_not_encourage` | Tidak bisa menyemangati | 1 | 0 | Bisa menyemangati lagi nanti.  |
| `taste_good` | Enak | 1 | 1 | Enak: kelelahan tertahankan.  |
| `taste_very_good` | Rasa surgawi | 1 | 1 | Sangat enak: hampir tak merasa lelah.  |
| `taste_bad` | Tidak enak | 1 | 1 | Tidak enak: kelelahan menumpuk. |
| `taste_very_bad` | Rasa terburuk | 1 | 1 | Sangat tidak enak: kelelahan cepat menumpuk. |
| `excited` | Bersemangat | 1 | 1 | Bersemangat: kelelahan tertahankan. |
| `effect_fresh` | Kafein | 1 | 1 | Aroma segar: pemakaian energi turun. |
| `newbie_shield_cheat` | (Cheat) Aroma modern | 1 | 0 | Hewan menghindari bau asing. |
| `rest_cheat` | (Cheat) Istirahat | 1 | 1 | Istirahat: lelah cepat pulih. |
| `rest` | Istirahat | 9 | 3 | Istirahat: lelah pulih. |
| `rest_ancora` | Istirahat | 100 | 1 | Istirahat: lelah pulih. |
| `rest_s02_bed` | Istirahat alas lumut | 100 | 3 | Istirahat di tempat layak: kelelahan luluh. |
| `rest_s02_shelter_01` | Istirahat gubuk lumut | 100 | 3 | Istirahat di tempat layak: kelelahan luluh. |
| `rest_cash` | Istirahat | 100 | 3 | Istirahat di tempat layak: kelelahan luluh. |
| `pool_rest` | Pakai kolam renang | 59 | 1 | Istirahat di kolam: jadi lapar. |
| `rest_pool_minor` | Pakai kolam renang | 60 | 1 | Istirahat di kolam: jadi lapar. |
| `rest_pool` | Pakai kolam renang | 60 | 1 | Istirahat di kolam: jadi lapar. |
| `rest_spa_minor` | Pakai pemandian terbuka | 60 | 1 | Istirahat di pemandian terbuka: jadi lapar. |
| `rest_spa` | Pakai pemandian terbuka | 60 | 1 | Istirahat di pemandian terbuka: jadi lapar. |
| `rest_bm_fatigue` | Istirahat kuat | 60 | 1 | Istirahat kuat: kelelahan turun cepat. |
| `rest_mount` | Istirahat | 60 | 3 | Istirahat: lelah pulih. |
| `inside` | Di dalam rumah | 1 | 7 | Di dalam ruangan: efek lingkungan berkurang. |
| `pleasant_fragrance` | Aroma menyenangkan | 1 | 11 | Aroma menyenangkan: kebal lelah akibat iklim.
Catatan: tidak berlaku untuk lelah lingkungan tak stabil (indeks II+, lv60+). |
| `under_roof` | Naungan | 1 | 3 | Di bawah naungan: terhindar dari panas. |
| `satiety_high` | Kenyang | 1 | 0 | Kenyang: tidak bisa makan lagi. |
| `fatigue_caution` | Lelah | 10 | 2 | Butuh istirahat: jika terus kerja tak bisa bergerak. |
| `fatigue_danger` | Kelelahan berat | 10 | 3 | Kelelahan berat: pulih hingga tahap lelah dulu agar bisa aktif. |
| `poisoning` | Keracunan | 30 | 1 | Keracunan: kesehatan turun. |
| `energetic` | Vitalitas | 2 | 1 | Bersemangat: pemakaian energi turun. |
| `dejected` | Frustasi | 1 | 1 | Frustasi: pemakaian energi naik. |
| `food_power` | Energi makanan | 1 | 0 | Stat naik sesuai jenis makanan. |
| `food_ability` | Peningkatan stat | 1 | 0 | Makan: kemampuan naik. |
| `food_survival` | Peningkatan survival | 1 | 0 | Makan: survival naik. |
| `away_from_keyboard` | AFK | 1 | 0 | Sedang AFK. |
| `raw_food` | Sakit perut | 1 | 1 | Salah makan mentah: kelelahan menumpuk. |
| `hot_food` | Makanan hangat | 5 | 4 | Makan hangat: dingin tertahankan. |
| `cold_food` | Makanan dingin | 5 | 4 | Makan dingin: panas tertahankan. |
| `life_up` | Regen HP naik | 10 | 1 | Efek makanan/obat: regen HP lebih cepat. |
| `health_up` | Regen kesehatan naik | 10 | 1 | Efek makanan/obat: kesehatan pulih perlahan. |
| `stamina_up` | Regen stamina naik | 10 | 1 | Efek makanan/obat: regen stamina lebih cepat. |
| `stance_attack_se` | Efek sikap serang | 5 | 1 |  |
| `stance_defense_se` | Efek sikap bertahan | 5 | 1 |  |
| `stance_counter_se` | Efek sikap serang balik | 5 | 1 |  |
| `stance_fierce_se` | Efek sikap gempur | 5 | 1 |  |
| `stance_charge_se` | Efek sikap menyerbu | 5 | 1 |  |
| `stance_shooting_se` | Efek sikap menembak | 5 | 1 |  |
| `stance_sniping_se` | Efek sikap sniper | 5 | 2 |  |
| `head_injury` | Cedera kepala | 1 | 1 | Kepala cedera. |
| `body_injury` | Cedera badan | 1 | 1 | Badan cedera. |
| `leg_injury` | Cedera kaki | 1 | 1 | Kaki cedera. |
| `tail_injury` | Cedera ekor | 1 | 1 | Ekor cedera. |
| `head_injury_raptor` | Gigi rusak | 1 | 1 | Gigi rusak: damage turun. |
| `head_injury_direwolf` | Gigi rusak | 1 | 1 | Gigi rusak: damage turun. |
| `head_injury_stego` | Gegar otak | 1 | 1 | Linglung: akurasi turun. |
| `head_injury_tricera` | Tanduk rusak | 1 | 1 | Tanduk rusak: damage turun. |
| `head_injury_brachio` | Gegar otak | 1 | 1 | Linglung: akurasi turun. |
| `body_injury_default` | Organ rusak | 6 | 1 | Organ rusak: regen HP melambat. |
| `leg_injury_raptor` | Gerak melambat | 1 | 1 | Kaki cedera: sulit menghindari serangan. |
| `leg_injury_direwolf` | Gerak melambat | 1 | 1 | Kaki cedera: sulit menghindari serangan. |
| `leg_injury_stego` | Gerak melambat | 1 | 1 | Kaki cedera: sulit menghindari serangan. |
| `leg_injury_tricera` | Gerak melambat | 1 | 1 | Kaki cedera: sulit menghindari serangan. |
| `leg_injury_brachio` | Gerak melambat | 1 | 1 | Kaki cedera: sulit menghindari serangan. |
| `tail_injury_raptor` | Kehilangan keseimbangan | 1 | 1 | Kehilangan keseimbangan: akurasi turun. |
| `tail_injury_direwolf` | Kehilangan keseimbangan | 1 | 1 | Kehilangan keseimbangan: akurasi turun. |
| `tail_injury_stego` | Otot ekor rusak | 1 | 1 | Otot ekor rusak: damage turun. |
| `tail_injury_tricera` | Kehilangan keseimbangan | 1 | 1 | Kehilangan keseimbangan: akurasi turun. |
| `tail_injury_brachio` | Otot ekor rusak | 1 | 1 | Otot ekor rusak: damage turun. |
| `death_penalty` | Pusing | 1 | 1 | Mual dan pusing: akurasi sedikit turun. |
| `death_count` | Efek samping revive | 1 | 0 | Makin sering mati: kesehatan revive makin kecil. |
| `death_aftereffect_revive_immediately` | Efek samping revive instan | 1 | 0 | Kesehatan revive turun, tapi hewan menghindari bau asing sementara. |
| `clan_gathering_plant` | Riset kumpul tumbuhan | 1 | 1 | Riset suku: kumpul tumbuhan naik. |
| `clan_gathering_mine` | Riset kumpul mineral | 1 | 1 | Riset suku: kumpul mineral naik. |
| `clan_gathering_animal` | Riset butcher hewan | 1 | 1 | Riset suku: butcher hewan naik. |
| `clan_craft_tool` | Riset buat alat | 1 | 3 | Riset suku: buat alat naik. |
| `clan_craft_clothes` | Riset buat pakaian | 1 | 2 | Riset suku: buat pakaian naik. |
| `clan_craft_cook` | Riset masak | 1 | 1 | Riset suku: masak naik. |
| `clan_craft_construction` | Riset bangun | 1 | 3 | Riset suku: kemampuan bangun naik. |
| `clan_adventure_survival` | Riset survival | 1 | 6 | Riset suku: survival naik. |
| `clan_adventure_ecology` | Riset ekologi | 1 | 2 | Riset suku: kemampuan ekologi naik. |
| `clan_combat_attack` | Riset serangan | 1 | 2 | Riset suku: serangan naik. |
| `clan_combat_defense` | Riset pertahanan | 1 | 2 | Riset suku: pertahanan naik. |
| `clan_combat_recovery` | Riset pemulihan | 1 | 2 | Riset suku: pemulihan naik. |
| `test_exp_bonus` | EXP naik | 10 | 1 | Status untuk uji internal. |
| `test_tstone_bonus` | Tstone naik | 10 | 1 | Status untuk uji internal. |
| `test_reduce_sail_cost` | Biaya layar turun | 1 | 1 | Status untuk uji internal. |
| `test_reduce_warp_cost` | Biaya warp turun | 1 | 1 | Status untuk uji internal. |
| `clan_prevent_item_drop` | Cegah barang hilang | 1 | 1 | Mati: kehilangan barang lebih sedikit (efek turun seiring level). |
| `clan_growth_buff` | Bonus suku | 1 | 1 | EXP suku terkumpul: efisiensi jelajah naik. |
| `login_shield` | Perlindungan | 1 | 0 | Sementara kebal dari target pemain lain. |
| `camp_fire` | Nyaman | 1 | 11 | Di camp: kurang lelah. |
| `poison_poo` | Racun kotoran | 19 | 1 | Kotoran di tangan sebabkan ruam: kelelahan naik. |
| `bleeding_neverstop` | Pendarahan aneh | 61 | 1 | Darah tak berhenti: kesehatan turun terus. |
| `dirty_saliva` | Penuh air liur | 61 | 1 | Penuh air liur: kelelahan naik.  |
| `tetanus` | Tetanus | 61 | 1 | Tergores cakar kotor: energi turun terus. |
| `bleeding_inner` | Pendarahan dalam | 61 | 1 | Terluka dalam: HP turun terus. |
| `poison_gas` | Bau busuk | 61 | 2 | Kena gas bau: akurasi dan sembunyi turun. |
| `poison_plant_moving` | Racun tumbuhan karnivora | 61 | 1 | Tersentuh batang beracun: kesehatan maks turun.  |
| `poison_lizard` | Racun kadal | 61 | 1 | Kena racun kadal: kesehatan maks turun. |
| `poison_bug_bee` | Sengatan lebah | 61 | 1 | Disengat lebah: peluang kritikal turun. |
| `poison_bug_sticky` | Gigitan serangga | 61 | 1 | Digigit serangga: akurasi turun.  |
| `poison_poison_sac` | Keracunan kantung racun | 61 | 1 | Ruam saat kumpul kantung racun: kelelahan naik. |
| `poison_heat` | Racun panas | 61 | 1 | Kena racun panas saat kumpul tropis: kesehatan turun. |
| `immune_collect` | Cegah ruam | 61 | 1 | Imun ruam hingga obat habis: cegah racun kotoran/kantung. |
| `immune_bleeding_neverstop` | Cegah pendarahan aneh | 61 | 1 | Cegah pendarahan aneh hingga obat habis. |
| `immune_tetanus` | Cegah tetanus | 61 | 1 | Cegah tetanus hingga obat habis. |
| `immune_bleeding_inner` | Cegah pendarahan dalam | 61 | 1 | Cegah pendarahan dalam hingga obat habis. |
| `immune_gas` | Cegah gas beracun | 61 | 1 | Imun gas beracun hingga obat habis. |
| `immune_plant_moving` | Cegah racun tumbuhan | 61 | 1 | Imun racun tumbuhan hingga obat habis. |
| `immune_lizard` | Cegah racun kadal | 61 | 1 | Imun racun kadal hingga obat habis. |
| `immune_bug` | Cegah racun serangga | 61 | 1 | Imun racun lebah/serangga hingga obat habis. |
| `cure_poison_collect` | Obati ruam  | 1 | 0 | Racun kotoran dan kantung racun dinetralkan. |
| `cure_bleeding_neverstop` | Netralkan racun darah | 1 | 0 | Racun darah pulih. |
| `cure_tetanus` | Obati tetanus | 1 | 0 | Tetanus sembuh. |
| `cure_bleeding_inner` | Obati pendarahan dalam | 1 | 0 | Pendarahan dalam pulih. |
| `cure_poison_gas` | Netralkan gas beracun | 1 | 0 | Gas beracun dinetralkan. |
| `cure_poison_plant_moving` | Netralkan racun tumbuhan | 1 | 0 | Racun tumbuhan karnivora dinetralkan. |
| `cure_poison_lizard` | Netralkan racun kadal | 1 | 0 | Racun kadal dinetralkan. |
| `cure_poison_bug` | Netralkan racun serangga | 1 | 0 | Bisa menetralkan racun lebah dan serangga. |
| `cure_poison_heat` | Obati & cegah racun panas | 1 | 1 | Obati dan cegah racun panas. |
| `cure_bleeding` | Efek pereda nyeri | 1 | 0 | Pereda nyeri: lupa sakit pendarahan. |
| `effect_coffee_drip` | Efek kopi | 60 | 1 | Kopi: frustasi hilang, lelah pulih. |
| `effect_coffee_dutch` | Efek kopi | 60 | 1 | Kopi: frustasi hilang, lelah pulih. |
| `vitalize` | Bangkit | 1 | 1 | Efek bangkit: bisa beraktivitas lebih lama. |
| `effect_cactus_juice` | Efek kaktus | 60 | 2 | Jus kaktus: tidak terlalu lelah. |
| `delight_of_discovery` | Sukacita penemuan | 60 | 1 | Menemukan titik penting: lupa lelah. |
| `30days_package` | Paket bulanan | 1 | 1 | Tiap hari via pos: ayam dan warp gem. |
| `7days_package` | Paket 7 hari | 1 | 1 | Berlangsung 7 hari |
| `15days_package` | Paket 15 hari | 1 | 1 | Berlangsung 15 hari |
| `welcome_package` | Paket level cepat | 1 | 2 | Berlaku hingga karakter/lineage lv60. |
| `selfimprovement_package` | Pengembangan diri | 1 | 2 |  |
| `exp_1.2_event` | Event EXP & skill 20% | 1 | 2 |  |
| `exp_1.5_event` | Event EXP & skill 50% | 1 | 2 |  |
| `exp_2_event` | Event EXP & skill 100% | 1 | 2 |  |
| `skill_exp_1.2_event` | Event skill 20% | 1 | 1 |  |
| `skill_exp_1.5_event` | Event skill 50% | 1 | 1 |  |
| `skill_exp_2_event` | Event skill 100% | 1 | 1 |  |
| `advanced_taming_research` | Riset jinakkan lanjut | 1 | 6 | Bisa menjinakkan lebih banyak jenis hewan. |
| `advanced_battle_research` | Riset tempur lanjut | 1 | 6 | Kemampuan tempur naik. |
| `advanced_gathering_research` | Riset kumpul lanjut | 1 | 1 | Peluang atribut laten/langka saat kumpul naik. |
| `life_incr` | Hentikan darah | 10 | 1 | Darah berhenti: HP naik. |
| `life_decr` | Pendarahan | 10 | 1 | Berdarah: HP turun. |
| `health_incr` | Regenerasi | 10 | 1 | Luka pulih: kesehatan naik. |
| `health_decr` | Luka dalam | 10 | 1 | Luka dalam: kesehatan turun. |
| `stamina_incr` | Terharu | 10 | 1 | Hal baik terjadi: stamina naik. |
| `stamina_decr` | Kecewa | 10 | 1 | Kecewa: stamina turun. |
| `energy_incr` | Semangat | 10 | 1 | Penuh semangat: energi naik. |
| `energy_decr` | Putus asa | 10 | 1 | Putus asa: energi turun. |
| `hit_rate_incr` | Fokus | 10 | 1 | Fokus: akurasi naik. |
| `hit_rate_decr` | Tidak fokus | 10 | 1 | Tak bisa fokus: akurasi turun. |
| `sadism` | Sadisme | 10 | 1 | HP naik. |
| `animal_rage` | Amarah | 60 | 1 | Amarah: serangan menguat. |
| `animal_exhausted` | Lelah | 60 | 1 | Lelah: sulit menghindar. |
| `life_allo_phase01` | Allosaurus bersemangat | 1 | 1 | Allosaurus bersemangat: HP pulih sedikit lebih banyak. |
| `life_allo_phase02` | Allosaurus mengamuk | 1 | 1 | Allosaurus mengamuk: HP pulih cepat. |
| `exertion_headache` | Sakit kepala olahraga | 1 | 0 | Kepala berdenyut: berbahaya mencoba pulih lebih jauh. |
| `test_selfimprovement_package` | Efek pengembangan diri uji | 1 | 2 | Waktu riset skill -20%, perolehan tstone +5%. |
| `attention` | Terprovokasi | 60 | 0 | Terprovokasi: tak bisa ganti target. |
| `survival_exp_1.5_event` | Event skill survival 50% | 1 | 1 |  |
| `survival_exp_2_event` | Event skill survival 100% | 1 | 1 |  |
| `survival_exp_3_event` | Event skill survival 200% | 1 | 1 |  |
| `survival_exp_4_event` | Event skill survival 300% | 1 | 1 |  |
| `melee_exp_1.5_event` | Event skill melee 50% | 1 | 1 |  |
| `melee_exp_2_event` | Event skill melee 100% | 1 | 1 |  |
| `melee_exp_3_event` | Event skill melee 200% | 1 | 1 |  |
| `melee_exp_4_event` | Event skill melee 300% | 1 | 1 |  |
| `ranged_exp_1.5_event` | Event skill panah 50% | 1 | 1 |  |
| `ranged_exp_2_event` | Event skill panah 100% | 1 | 1 |  |
| `ranged_exp_3_event` | Event skill panah 200% | 1 | 1 |  |
| `ranged_exp_4_event` | Event skill panah 300% | 1 | 1 |  |
| `defense_exp_1.5_event` | Event skill bertahan 50% | 1 | 1 |  |
| `defense_exp_2_event` | Event skill bertahan 100% | 1 | 1 |  |
| `defense_exp_3_event` | Event skill bertahan 200% | 1 | 1 |  |
| `defense_exp_4_event` | Event skill bertahan 300% | 1 | 1 |  |
| `butchery_exp_1.5_event` | Event skill butcher 50% | 1 | 1 |  |
| `butchery_exp_2_event` | Event skill butcher 100% | 1 | 1 |  |
| `butchery_exp_3_event` | Event skill butcher 200% | 1 | 1 |  |
| `butchery_exp_4_event` | Event skill butcher 300% | 1 | 1 |  |
| `gathering_exp_1.5_event` | Event skill kumpul 50% | 1 | 1 |  |
| `gathering_exp_2_event` | Event skill kumpul 100% | 1 | 1 |  |
| `gathering_exp_3_event` | Event skill kumpul 200% | 1 | 1 |  |
| `gathering_exp_4_event` | Event skill kumpul 300% | 1 | 1 |  |
| `cooking_exp_1.5_event` | Event skill masak 50% | 1 | 1 |  |
| `cooking_exp_2_event` | Event skill masak 100% | 1 | 1 |  |
| `cooking_exp_3_event` | Event skill masak 200% | 1 | 1 |  |
| `cooking_exp_4_event` | Event skill masak 300% | 1 | 1 |  |
| `weaponcrafting_exp_1.5_event` | Event skill senjata/alat 50% | 1 | 1 |  |
| `weaponcrafting_exp_2_event` | Event skill senjata/alat 100% | 1 | 1 |  |
| `weaponcrafting_exp_3_event` | Event skill senjata/alat 200% | 1 | 1 |  |
| `weaponcrafting_exp_4_event` | Event skill senjata/alat 300% | 1 | 1 |  |
| `armorcrafting_exp_1.5_event` | Event skill pakaian 50% | 1 | 1 |  |
| `armorcrafting_exp_2_event` | Event skill pakaian 100% | 1 | 1 |  |
| `armorcrafting_exp_3_event` | Event skill pakaian 200% | 1 | 1 |  |
| `armorcrafting_exp_4_event` | Event skill pakaian 300% | 1 | 1 |  |
| `constructing_exp_1.5_event` | Event skill bangun 50% | 1 | 1 |  |
| `constructing_exp_2_event` | Event skill bangun 100% | 1 | 1 |  |
| `constructing_exp_3_event` | Event skill bangun 200% | 1 | 1 |  |
| `constructing_exp_4_event` | Event skill bangun 300% | 1 | 1 |  |
| `farming_exp_1.5_event` | Event skill tani 50% | 1 | 1 |  |
| `farming_exp_2_event` | Event skill tani 100% | 1 | 1 |  |
| `farming_exp_3_event` | Event skill tani 200% | 1 | 1 |  |
| `farming_exp_4_event` | Event skill tani 300% | 1 | 1 |  |
| `process_exp_1.5_event` | Event skill olah 50% | 1 | 1 |  |
| `process_exp_2_event` | Event skill olah 100% | 1 | 1 |  |
| `process_exp_3_event` | Event skill olah 200% | 1 | 1 |  |
| `process_exp_4_event` | Event skill olah 300% | 1 | 1 |  |
| `weaponcraft_plus_01_event` | Event buat senjata naik | 1 | 1 | Kemampuan buat senjata naik. |
| `armorcraft_plus_01_event` | Event buat pakaian naik | 1 | 1 | Kemampuan buat pakaian naik. |
| `tailor_plus_01_event` | Event jahit naik | 1 | 1 | Kemampuan jahit naik. |
| `handicraft_plus_01_event` | Event kerajinan naik | 1 | 1 | Kemampuan kerajinan naik. |
| `smith_plus_01_event` | Event olah logam naik | 1 | 1 | Kemampuan olah logam naik. |
| `construction_plus_01_event` | Event bangun naik | 1 | 1 | Kemampuan bangun naik. |
| `furnishing_plus_01_event` | Event buat furnitur naik | 1 | 1 | Kemampuan membuat furnitur naik. |
| `cook_plus_01_event` | Event masak naik | 1 | 1 | Kemampuan masak naik. |
| `farming_plus_01_event` | Event tani naik | 1 | 1 | Kemampuan tani naik. |
| `gathering_plus_01_event` | Event kumpul tumbuhan naik | 1 | 1 | Kemampuan kumpul tumbuhan naik. |
| `mining_plus_01_event` | Event tambang naik | 1 | 1 | Kemampuan tambang naik. |
| `butchering_plus_01_event` | Event butcher naik | 1 | 1 | Kemampuan butcher naik. |
| `returner` | Perintis kembali | 60 | 1 |  |
| `nausea` | Mual | 1 | 1 | Mual karena kelelahan pulau minyak. Turunkan kelelahan hingga batas tertentu. |
| `headache` | Linglung | 1 | 2 | Linglung karena iklim pulau minyak. Turunkan kelelahan hingga batas tertentu. |
| `mental_confusion` | Linglung | 1 | 4 | Linglung karena iklim pulau minyak. Turunkan kelelahan hingga batas tertentu. |
| `s02_inside` | Efek shelter kabut | 1 | 2 | Ruangan anti iklim pulau minyak: mengurangi efek kabut minyak. |
| `s02_inside_02` | Efek shelter kabut cerobong | 1 | 2 | Ruangan anti iklim pulau minyak: sangat mengurangi efek kabut minyak. |
| `poison_oil` | Racun minyak | 1 | 1 | Kena racun minyak saat kumpul: kesehatan sedikit turun. Pakaian tepat mengurangi peluang. |
| `s02_longlife` | Efek makanan stabil | 10 | 1 | Makanan stabil: regen HP dan kelelahan naik. |
| `cure_poison_oil` | Netralkan racun minyak | 1 | 0 | Racun minyak dinetralkan. |
| `immune_poison_oil` | Imun racun minyak | 20 | 1 | Imun damage racun minyak selama durasi. |
| `s02_energetic` | Vitalitas | 1 | 1 | Bersemangat: kelelahan sedikit turun. |
| `pet_master_charming` | Kelucuan meledak | 10 | 1 | Melihat tingkah lucu: kelelahan turun. |
| `pet_exp_1.2` | EXP hewan +20% | 1 | 1 | EXP hewan pendamping +20% (tidak tumpuk dengan event EXP karakter). |
| `pet_exp_1.5` | EXP hewan +50% | 1 | 1 | EXP hewan pendamping +50% (tidak tumpuk dengan event EXP karakter). |
| `pet_exp_2` | EXP hewan +100% | 1 | 1 | EXP hewan pendamping +100% (tidaktumpuk dengan event EXP karakter). |
| `pet_life_incr` | HP pet naik | 10 | 1 | Darah berhenti: HP naik. |
| `pet_exp_1.2_event` | EXP hewan +20% | 1 | 1 | EXP hewan pendamping +20% (tidak tumpuk dengan event EXP karakter). |
| `pet_exp_1.5_event` | EXP hewan +50% | 1 | 1 | EXP hewan pendamping +50% (tidak tumpuk dengan event EXP karakter). |
| `pet_exp_2_event` | EXP hewan +100% | 1 | 1 | EXP hewan pendamping +100% (tidaktumpuk dengan event EXP karakter). |
| `pet_speed_amplifier` | Kecepatan hewan amplified | 10 | 1 | Kecepatan hewan amplified. |
| `pet_speed_plus` | Kecepatan hewan naik | 10 | 1 | Kecepatan hewan naik. |
| `pet_bag_amplifier` | Kapasitas tas hewan amplified | 10 | 1 | Kapasitas tas hewan amplified. |
| `pet_bag_plus` | Kapasitas tas hewan naik | 10 | 1 | Kapasitas tas hewan naik. |
| `pet_attack_amplifier` | Serangan hewan amplified | 10 | 1 | Serangan hewan amplified. |
| `pet_attack_plus` | Serangan hewan naik | 10 | 1 | Serangan hewan naik. |
| `pet_defense_amplifier` | Pertahanan hewan amplified | 10 | 1 | Pertahanan hewan amplified. |
| `pet_defense_plus` | Pertahanan hewan naik | 10 | 1 | Serangan hewan naik. |
| `pet_cooltime_ratio` | Cooldown hewan turun | 10 | 1 | Cooldown hewan turun: menyerang lebih cepat. |
| `pet_life_max_amplifier` | HP maks hewan amplified | 10 | 1 | HP maks hewan amplified. |
| `pet_life_max_plus` | HP maks hewan naik | 10 | 1 | HP maks hewan naik. |
| `pet_life_regen_amplifier` | Regen hewan amplified | 10 | 1 | Regen HP hewan per jam amplified. |
| `pet_life_regen_plus` | Regen hewan naik | 10 | 1 | Regen HP hewan per jam naik. |
| `pet_accuracy_amplifier` | Akurasi hewan amplified | 10 | 1 | Akurasi hewan saat menyerang amplified. |
| `pet_accuracy_plus` | Akurasi hewan naik | 10 | 1 | Akurasi hewan saat menyerang naik. |
| `clean_pet` | Dijilat hewan | 10 | 1 | Dijilat hewan: bersih, panas dan lelah tertahankan. |
| `clean_pet_02` | Cuci muka air laut | 10 | 1 | Hewan menyiram air laut: bersih, panas dan lelah tertahankan. |
| `life_up_pet` | Dukungan medis | 10 | 1 | Dukungan hewan: HP pulih perlahan. |
| `stamina_up_pet` | Dukungan belakang | 10 | 1 | Dukungan hewan: stamina regen lebih cepat. |
| `pet_vitality_ratio` | Vitalitas hewan awet | 10 | 1 | Penurunan vitalitas hewan melambat. |
| `excited_pet` | Keramahan | 10 | 1 | Hewan bersikap ramah: kelelahan tertahankan. |
| `energetic_pet` | Gotong royong | 10 | 1 | Bantuan hewan: pemakaian energi turun. |
| `mood_bubbly` | Suasana lucu | 30 | 0 | Energi maks naik. |
| `mood_horrible` | Suasana suram | 30 | 0 | Jarak serang duluan hewan turun. |
| `mood_luxurious` | Suasana mewah | 30 | 0 | Makan masakan: durasi kenyang turun. |
| `energy_regen_by_food` | Regen energi | 1 | 0 | Makan: energi regen terus. |
| `set_bedroom` | Efek set kamar | 60 | 0 | Efek dari susunan set. |
| `set_kitchen` | Efek set dapur | 60 | 0 | Efek dari susunan set. |
| `set_drawingroom` | Efek set ruang tamu | 60 | 0 | Efek dari susunan set. |
| `set_dressroom` | Efek set ruang pakaian | 60 | 0 | Efek dari susunan set. |
| `search_poi` | Efek samping eksplorasi | 60 | 1 | Setelah eksplorasi: energi turun. |
| `fatigue_warning` | Lelah | 10 | 1 | Lelah dan lapar menumpuk. |
| `fatigue_notice` | Payah | 10 | 1 | Payah hingga lapar. |
| `living_tech_butchering` | Riset butcher | 3 | 1 | Kemampuan butcher naik. |
| `living_tech_armorcraft` | Riset pakaian | 3 | 1 | Kemampuan buat pakaian naik. |
| `living_tech_tailor` | Riset jahit | 3 | 1 | Kemampuan jahit naik. |
| `living_tech_cook` | Riset masak | 3 | 1 | Kemampuan masak naik. |
| `living_tech_dodge` | Riset hindar | 1 | 1 | Kemampuan hindar naik. |
| `living_tech_energy` | Riset energi | 1 | 1 | Energi maks naik. |
| `living_tech_hiding` | Riset sembunyi | 1 | 1 | Kemampuan sembunyi naik. |
| `light_tech_gathering` | Riset kumpul tumbuhan | 3 | 1 | Kemampuan kumpul tumbuhan naik. |
| `light_tech_farming` | Riset tani | 3 | 1 | Kemampuan tani naik. |
| `light_tech_handicraft` | Riset kerajinan | 3 | 1 | Kemampuan kerajinan naik. |
| `light_tech_furnishing` | Riset furnitur | 3 | 1 | Kemampuan membuat furnitur naik. |
| `light_tech_attack` | Riset serangan | 1 | 1 | Serangan naik. |
| `light_tech_accuracy` | Riset akurasi | 1 | 1 | Akurasi tempur naik. |
| `heavy_tech_disassembling` | Riset bongkar | 3 | 1 | Kemampuan bongkar naik. |
| `heavy_tech_mining` | Riset tambang | 3 | 1 | Kemampuan tambang naik. |
| `heavy_tech_weaponcraft` | Riset senjata | 3 | 1 | Kemampuan buat senjata naik. |
| `heavy_tech_smith` | Riset logam | 3 | 1 | Kemampuan olah logam naik. |
| `heavy_tech_construction` | Riset bangun | 3 | 1 | Kemampuan bangun naik. |
| `heavy_tech_attack_rating` | Riset tembus armor | 1 | 1 | Tembus armor naik. |
| `heavy_tech_critical` | Riset kritikal | 4 | 1 | Kritikal tempur naik. |
| `temporary_fortune_craft` | Keberuntungan sekali: craft | 1 | 1 | Peluang sukses besar craft berikutnya naik. |
| `temporary_concentration_craft` | Konsentrasi sekali: craft | 1 | 1 | Tingkat sukses craft berikutnya naik, bisa melampaui 99%. |
| `rainy_fortune_collect` | Hoki hujan: kumpul | 1 | 1 | Hari hujan: peluang sukses besar kumpul naik. |
| `rainy_fortune_craft` | Hoki hujan: craft | 1 | 1 | Hari hujan: peluang sukses besar craft naik. |
| `stable_immersion_collect` | Fokus stabil: kumpul | 1 | 1 | Waktu kumpul di pulau pribadi/kota lebih singkat. |
| `stable_immersion_craft` | Fokus stabil: craft | 1 | 1 | Waktu craft di pulau pribadi/kota lebih singkat. |
| `sadism_minor` | Sadisme kecil | 10 | 1 | HP sedikit naik. |
| `eat_bizarre_food` | Makanan aneh | 1 | 1 | Kalau ini saja dimakan, apa yang tidak bisa. |
| `mood_classroom01` | Suasana kelas | 1 | 0 | Belajar: waktu riset skill turun. |
| `mood_classroom02` | Suasana rajin belajar | 1 | 0 | Suasana rajin: waktu riset skill turun. |
| `mood_springtime` | Suasana musim semi | 30 | 0 | Aura musim semi: rasanya hal baik akan terjadi. |
| `energy_regen_by_trampoline_01` | Semangat meledak! | 1 | 1 | Kesenangan besar: energi meledak. |
| `energy_regen_by_rocking_horse_01` | Jiwa anak-anak | 1 | 2 | Nostalgia masa kecil: hati dan tubuh pulih.  |
| `test_skill_package` | Paket skill | 1 | 3 | Berlaku hingga karakter/lineage lv55. |
| `welcome_package_55lv` | Paket cepat lv55 | 1 | 3 | Hingga lv55. Riset skill instan selesai! |
| `premium_support_package` | Paket dukungan lanjut | 1 | 3 | Waktu craft/kumpul/bangun/tani turun, sukses naik!
Bonus harian: buka peta, revive instan, batal belajar skill. |
| `warp_rush_reward_increase_50` | Hadiah warp rush +50% | 1 | 1 | Warp rush: semua stone +50% (total 150%). |
| `warp_rush_reward_increase_100` | Hadiah warp rush +100% | 1 | 1 | Warp rush: semua stone +100% (total 200%). |
| `warp_rush_reward_increase_200` | Hadiah warp rush +200% | 1 | 1 | Warp rush: semua stone +200% (total 300%). |
| `artifact_reaction_heat_resistant` | Pakai bangunan | 1 | 3 | Pakai bangunan: resistensi iklim naik. |
| `random_number_piece_package` | Paket pecahan acak | 1 | 0 | Dapat 30 pecahan acak tiap hari. |
| `effect_jasmine` | Aroma melati | 2 | 1 | Aroma melati: pemakaian energi turun. |
| `life_health_up_pet` | Festival mulai! | 10 | 2 | Dukungan meriah: HP dan kesehatan pulih. |
| `drunk` | Segar | 1 | 2 | Minuman segar: kelelahan tertahankan! |
| `artifact_reaction_great_success_plus` | Pakai bangunan | 1 | 1 | Pakai bangunan: peluang sukses besar craft naik. |
| `master_attack_up_pet` | Lebih keras! | 3 | 1 | Dukungan Compy badut: serangan naik.  |
| `unlimited_pet_vigor` | Vitalitas tak terbatas | 30 | 1 | Vitalitas hewan tidak berkurang. |
| `unlimited_pet_vigor_1d` | Vitalitas tak terbatas | 1 | 1 | Vitalitas hewan tidak berkurang. |
| `tea_effect_01` | Peningkatan stat | 70 | 1 | Makan: kemampuan naik. |
| `tea_effect_02` | Peningkatan stat | 70 | 1 | Makan: kemampuan naik. |
| `unlimited_pet_vigor_3d` | Vitalitas tak terbatas | 1 | 1 | Vitalitas hewan tidak berkurang. |
| `event_reduce_warp_cost` | Biaya warp turun | 1 | 1 | Biaya warp turun |
| `clean_volcanic_lake_01` | Berendam: regen kesehatan | 10 | 1 | Onsen: luka cepat sembuh, kesehatan regen terus. |
| `clean_volcanic_lake_02` | Berendam: serangan naik | 10 | 1 | Onsen: bertenaga, serangan naik. |
| `wet_volcanic_lake` | Basah onsen | 10 | 2 | Berendam onsen: aman dari badai vulkanik. |
| `volcanic_storm_sign` | Pertanda | 10 | 1 | Stamina turun terus: badai vulkanik segera datang. |
| `volcanic_storm` | Badai vulkanik | 10 | 1 | Kesehatan turun terus. Masuk onsen atau pakai baju tambang badai vulkanik. |
| `lava` | Kena lava | 10 | 1 | Kena lava: HP turun besar.  |
| `burn` | Luka bakar | 10 | 1 | Luka bakar: kesehatan turun terus. Masuk ke air terdekat. |
| `immune_lava` | Imun lava | 1 | 1 | Imun damage lava. |
| `immune_volcanic_storm` | Imun badai vulkanik | 1 | 1 | Imun damage badai vulkanik. |
| `mood_fiery` | Suasana panas | 30 | 0 | Serangan naik. |
| `iguana_great_success_craft` | Tangan berkilau | 10 | 1 | Peluang sukses besar craft naik. |
| `tyrano_shout` | Raungan Tyranno | 10 | 1 | Raungan Tyranno: gendang telinga rusak parah. |
| `immune_tyrano_shout` | Pelindung gendang telinga | 10 | 1 | Tak dengar raungan Tyranno. |
| `iguana_fire_dung` | Percikan api | 10 | 1 | Kena percikan Iguana: damage turun. |
| `immune_iguana_fire_dung` | Cegah percikan api | 10 | 1 | Imun serangan percikan Iguana bintik api. |
| `tyrano_bruise` | Memar | 10 | 1 | Kena sundulan Tyranno: memar. |
| `tyrano_rage_01` | Tyrannosaurus bersemangat | 1 | 2 | Tyrannosaurus bersemangat: serangan lebih kuat. |
| `tyrano_rage_02` | Tyrannosaurus mengamuk | 1 | 2 | Tyrannosaurus mengamuk: serangan sangat kuat. |
| `tyrano_rage_03` | Tyrannosaurus murka | 1 | 2 | Tyrannosaurus murka: serangan tak tertahankan. |
| `hadro_cheer_up` | Dukungan tempur | 10 | 6 | Kemampuan tempur naik. |
| `immune_burn` | Imun luka bakar | 10 | 1 | Imun damage luka bakar. |
| `artifact_reaction_volcanic_heat_resistant` | Pakai sauna | 1 | 1 | Efek rendam dingin: lebih tahan panas vulkanik. |
| `food_energy_incr` | Regen energi terus | 10 | 1 | Penuh nutrisi: energi naik terus. |
| `event_statue_aura` | Aura patung | 1 | 2 |  |
| `rest_sauna_01` | Pakai sauna | 60 | 2 | Istirahat di tempat layak: kelelahan luluh. |
| `immune_lava_2` | Imun lava | 1 | 1 | Imun damage lava. |
| `food_max_health_energy_incr` | Manis bertenaga | 60 | 2 | Makanan lezat: kesehatan maks dan energi maks naik. |
| `food_fatigue_decr` | Minuman dingin | 60 | 1 | Minuman dingin: kelelahan pulih. |
| `engagement_reward` | Cek fokus bermain | 1 | 2 | Kesehatan maks +150, energi maks +50. |
| `pvp_fog` | Kabut | 1 | 0 | Kabut menutup pandangan: tak bisa masuk mode tempur, bisa ganti alat/makan. |
| `pvp_rain` | Hujan | 1 | 0 | Kabut hilang: masuk mode tempur, tak bisa keluar mode/pakai item. |
| `pvp_storm` | Badai | 1 | 1 | Badai: kesehatan turun. Berlindung di shelter. |
| `pvp_hypothermy` | Hipotermia | 1 | 1 | Badai terlalu kuat, shelter tak membantu: kesehatan turun. |
| `pvp_shelter` | Evakuasi | 1 | 1 | Berlindung di shelter: kesehatan tidak turun. |
| `climate_nervous` | Gelisah | 1 | 0 | Badai kuat tak biasa: aura gelisah menyelimuti pulau. |
| `climate_strange_phenomenon` | Fenomena aneh | 1 | 0 | Spam warp: cuaca aneh berlanjut di Durango. |
| `fruit_sandwich_effects` | Sandwich buah | 1 | 9 | Makan: kemampuan naik. |
| `epic_lama_deodorant` | Hilang bau | 60 | 1 | Hilangkan bau badan: hewan tak menyadari. |
