# Скины НПС и мобов JediCraft

64×64 PNG, формат Minecraft 1.12.2 (второй слой включён). Собраны генератором `tools/skin-gen` из слоёв «Конструктора скинов» (тело, глаза, брови, причёски, одежда — с его же алгоритмом перекраски) плюс дорисованные Star Wars-детали: броня клонов и мандалорцев, шлемы, лекку, морды пришельцев, дроиды, мечи, плащи.

Колонка «Где подключается» — место в конфиге или коде, где сейчас стоит URL старого скина (или пусто). Чтобы подключить скин, PNG нужно выложить по публичному URL и подставить этот URL туда.

## НПС кантины

| Персонаж | Файл | Где подключается |
|---|---|---|
| Крупье Греедо | `cantina/cantina_greedo.png` | cantina/cantina.yml → tables.detonators.skin |
| Твилек Лира | `cantina/cantina_twilek_lira.png` | cantina/cantina.yml → tables.sabacc.skin |
| Джава Утини | `cantina/cantina_jawa_utini.png` | cantina/cantina.yml → tables.dice.skin |
| Гамореанец Гурк | `cantina/cantina_gamorrean_gurk.png` | cantina/cantina.yml → tables.duel.skin |
| Дурос Кэд | `cantina/cantina_duros_kad.png` | cantina/cantina.yml → tables.matches.skin |
| Букмекер Ботан | `cantina/cantina_bothan_botan.png` | cantina/cantina.yml → tables.races.skin |

## Квестовые НПС (портреты в диалогах Wada и сами НПС)

| Персонаж | Файл | Где подключается |
|---|---|---|
| Мастер Кайн Соларис | `quest/quest_kain_solaris.png` | dialogs.json «Кайн»; Skins.KAIN; mobs.yml tutorial_jedi |
| Джейн (архивист) | `quest/quest_jane.png` | dialogs.json «Джейн»; Skins.JANE |
| Клинт (пилот-контрабандист) | `quest/quest_clint.png` | dialogs.json «Клинт»; Skins.CLINT |
| Карас (гунган) | `quest/quest_karas.png` | dialogs.json «Карас»; KaminoQuests HEAD_KARAS; mobs.yml karas_personal |
| Буро-Баас (вождь гунганов) | `quest/quest_buro_baas.png` | dialogs.json «Буро-Баас» |
| Старейшина гунганов | `quest/quest_gungan_elder.png` | dialogs.json «Старейшина» |
| Страж гунганов | `quest/quest_gungan_guard.png` | dialogs.json «Страж гунганов» |
| Неизвестный гунган | `quest/quest_gungan_unknown.png` | dialogs.json «Неизвестный гунган» |
| Командир патруля (Набу) | `quest/quest_naboo_patrol_cmd.png` | dialogs.json «Командир патруля» |
| Тёмная фигура / Дарт Малакарион | `quest/quest_dark_figure.png` | dialogs.json «Тёмная фигура»; Skins.MALAKARION; mobs.yml tutorial_sith, darth_malakarion |
| Дух Дарт Треи | `quest/quest_spirit_traya.png` | dialogs.json «Дух Дарт Треи» |
| Дух Дарта Сиона | `quest/quest_spirit_sion.png` | dialogs.json «Дух Дарта Сиона» |
| Дух Дарта Нихилуса | `quest/quest_spirit_nihilus.png` | dialogs.json «Дух Дарта Нихилуса» |
| Бармен (Мос-Эйсли) | `quest/quest_barman.png` | QuestDesertSpirit/QuestShadyGuy HEAD_BARMAN; ResellerNpc |
| Биб Фортуна (тви'лек-мажордом) | `quest/quest_bib_fortuna.png` | Skins.BIB (HEAD_VEX, Quest002 «Биб Фортуна») |
| Главарь рейдеров | `quest/quest_raider_leader.png` | Skins.RAIDER_LEADER (Quest002, HEAD_SKRAB) |
| Страж лагеря / рейдер | `quest/quest_camp_guard.png` | Skins.CAMP_GUARD, Skins.RAIDER; mobs.yml reider_* |
| Лидер джав / джава-скупщик | `quest/quest_jawa_leader.png` | Skins.JAWA (HEAD_JAWA, Quest002 «Лидер Джав»); mobs.yml jawa |
| Дроид-переводчик | `quest/quest_protocol_droid.png` | Quest002 «Дроид-переводчик» (HEAD_DROID) |
| Дух Пустыни | `quest/quest_desert_spirit.png` | QuestDesertSpirit HEAD_SPIRIT; QuestKraytHeart «Дух пустыни» |
| Учёный (заброшенный институт) | `quest/quest_scientist.png` | QuestAbandonedInstitute HEAD_SCIENTIST |
| Командир отряда клонов-изгоев | `quest/quest_badbatch_commander.png` | QuestBadBatch HEAD_COMMANDER; Skins.COMMANDER (Коммандер Дейн) |
| Варра Тесс (охотница-мандалорка) | `quest/quest_varra_tess.png` | QuestBountyHunt HEAD_VARRA |
| Тико Ранн (беглый должник) | `quest/quest_tiko_rann.png` | QuestBountyHunt «Тико Ранн» |
| Джава-информатор | `quest/quest_jawa_informant.png` | QuestBountyHunt «Джава-информатор» |
| Z-01 (мятежный дроид) | `quest/quest_z01.png` | QuestDroidUprising «Z‑01» |
| Богатый торговец | `quest/quest_rich_merchant.png` | QuestDroidUprising «Богатый торговец» (HEAD_MERCHANT) |
| Векс Орро (бывший гонщик) | `quest/quest_vex_orro.png` | QuestKraytHeart HEAD_VEX (сейчас Skins.BIB) |
| Скар Валло (гонщик) | `quest/quest_skar_vallo.png` | QuestKraytHeart HEAD_SKAR / KraytHeartRuntime.SKIN_SKAR |
| Мира Сол (караванщица) | `quest/quest_mira_sol.png` | QuestLostCaravan «Мира Сол» |
| Погонщик Бен | `quest/quest_driver_ben.png` | QuestLostCaravan «Погонщик Бен» (HEAD_DRIVER) |
| Скраб (главарь банды) | `quest/quest_skrab.png` | QuestLostCaravan «Скраб» (HEAD_SKRAB) |
| Дорен Келл (влагодобытчик) | `quest/quest_doren_kell.png` | QuestMoistureFarm «Дорен Келл» |
| Робин (тёмный тип) | `quest/quest_robin.png` | QuestShadyGuy «Робин», «Неизвестный» |
| Китонак (старец) | `quest/quest_kitonak_npc.png` | QuestYoungWarrior «Китонак»; mobs.yml kitonak* |
| Молодой таскен | `quest/quest_young_tusken.png` | QuestYoungWarrior «Молодой Таскен»; HEAD_TUSKEN |
| Представитель Биба Фортуны | `quest/quest_fortuna_envoy.png` | QuestOldDebts «Представитель Биба Фортуны» |
| R7-X (астромех) | `quest/quest_r7x.png` | GeonosisQuests HEAD_R7 |
| Кьюрра (джеонозийка-старуха) | `quest/quest_kyurra.png` | GeonosisQuests HEAD_KYURRA (geonosian_man.png) |
| Падаван Нира | `quest/quest_padawan_nira.png` | GeonosisQuests HEAD_PADAWAN_1 (QuestDesertSpirit.PRISONER_1) |
| Пленная джедайка | `quest/quest_captive_jedi.png` | GeonosisQuests HEAD_CAPTIVE |
| Надзиратель Морг Кал | `quest/quest_morg_kal.png` | GeonosisQuests HEAD_MORG (inquisitors_guard.png) |
| Скупщик Ззик (джеонозиец) | `quest/quest_zzik.png` | GeonosisQuests HEAD_ZZIK (WarriorGeonosis.png) |
| Тон Ве (каминоанка) | `quest/quest_ton_we.png` | KaminoQuests HEAD_TONWE (сейчас ko_sai.png) |
| Лам Су (каминоанец-администратор) | `quest/quest_lam_su.png` | KaminoSideQuests HEAD_LAM (сейчас ko_sai.png) |
| Ро Нуа (каминоанка-генетик) | `quest/quest_ro_nua.png` | KaminoSideQuests HEAD_RO (сейчас ko_sai.png) |
| КТ-99 (клон-ветеран) | `quest/quest_ct99.png` | KaminoSideQuests HEAD_99 (сейчас field_automatic_clone.png) |
| Меддроид 2-1Б-7 | `quest/quest_meddroid.png` | KaminoSideQuests HEAD_MEDDROID |
| Агент Вейл (имперская разведка) | `quest/quest_agent_veil.png` | KaminoSideQuests HEAD_VEIL |
| Рейзор (сорванный клон) | `quest/quest_razor.png` | KaminoSideRuntime SKIN_RAZOR; mobs.yml razor_personal |
| Коммандер Корт (флот Республики) | `quest/quest_space_cmd_kort.png` | SpaceRuntime JEDI officerSkin |
| Механик Тэн | `quest/quest_space_mech_ten.png` | SpaceRuntime JEDI mechSkin |
| Пилот Ри Вейд | `quest/quest_space_pilot_ri.png` | SpaceRuntime JEDI pilotSkin |
| Связистка Мара | `quest/quest_space_comms_mara.png` | SpaceRuntime JEDI commsSkin |
| Инструктор Блиц | `quest/quest_space_instr_blitz.png` | SpaceRuntime JEDI instrSkin |
| Моф Ксандр Векк | `quest/quest_space_moff_vekk.png` | SpaceRuntime SITH officerSkin |
| Механик-дроид Ю-9 | `quest/quest_space_mech_u9.png` | SpaceRuntime SITH mechSkin |
| Пилот Сайра Кор | `quest/quest_space_pilot_saira.png` | SpaceRuntime SITH pilotSkin |
| Связист Делл | `quest/quest_space_comms_dell.png` | SpaceRuntime SITH commsSkin |
| Инструктор Рейк (теневой штурмовик) | `quest/quest_space_instr_reik.png` | SpaceRuntime SITH instrSkin |

## Новые мобы и боссы

| Персонаж | Файл | Где подключается |
|---|---|---|
| Учебный дроид | `mob/mob_training_droid.png` | mobs.yml training_droid_personal (model SKELETON) |
| Боевой дроид B1 | `mob/mob_b1_droid.png` | mobs.yml b1_droid_personal, clone_trooper (model SKELETON) |
| IG-100 Магнастраж | `mob/mob_magnaguard.png` | mobs.yml magnaguard, magnaguard_personal |
| Инквизитор Кассар | `mob/mob_inquisitor_kassar.png` | mobs.yml inquisitor_personal; SpaceRuntime JEDI bossName |
| Республиканский коммандос | `mob/mob_republic_commando.png` | mobs.yml republic_commando_personal |
| Мастер-джедай Орвин Кел | `mob/mob_jedi_orvin_kel.png` | mobs.yml jedi_master_personal; SpaceRuntime SITH bossName |
| Клон 104 батальона (страж) | `mob/mob_elite_guard.png` | mobs.yml elite_guard_personal, elite_*_clone |
| Прототип Ноль КК-0 | `mob/mob_prototype_zero.png` | mobs.yml prototype_zero_personal |
| Порабощённый клон | `mob/mob_enslaved_clone.png` | mobs.yml enslaved_academic, enslaved_clone_personal |
| Тень Тирануса | `mob/mob_tyranus_shadow.png` | mobs.yml tyranus_shadow_personal |
| Алый гвардеец | `mob/mob_royal_guard.png` | mobs.yml sidious_royal_guard |
| Теневой гвардеец | `mob/mob_shadow_guard.png` | mobs.yml sidious_shadow_guard, imperal_shadow_guard; HEAD_VEIL (старый) |
| Двойник Кэд Бэйна | `mob/mob_cad_bane_clone.png` | mobs.yml cad_bane_clone |
| Мандалорец Дозора Смерти | `mob/mob_mandalorian.png` | mobs.yml mandalorian |
| Глава Дозора Смерти | `mob/mob_mandalorian_boss.png` | mobs.yml mandalorian_boss |
| Отрёкшийся | `mob/mob_otrek.png` | mobs.yml otrek |
| Джеонозианский житель | `mob/mob_geonosian_resident.png` | mobs.yml geonosian_resident |
| Джеонозиец-воин | `mob/mob_geonosian_warrior.png` | mobs.yml geonosian_warrior, geonosian_warrior_personal |
| Порабощённый шахтёр | `mob/mob_enslaved_miner.png` | mobs.yml enslaved_miner*, enslaved_runner* |
| Порабощённый альфа-паразитом | `mob/mob_enslaved_alpha.png` | mobs.yml enslaved_alfa, enslaved_old, enslaved_beta |

Превью: `_preview_cantina.png`, `_preview_quest.png`, `_preview_mob.png` (вид спереди и сзади).
