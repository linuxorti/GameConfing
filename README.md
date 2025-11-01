# GameConfing
linuxorti.github.io

# Game_Confing
; damage_config.ini
[WeaponDamage]
; Базовый множитель урона для всего оружия (значение 1.0 = стандартный урон)
GlobalDamageMultiplier=991.25

[PlayerStats]
; Множитель урона для игрока (если применимо)
PlayerDamageMultiplier=105.55

[SpecificWeapons]
; Урон для конкретного оружия
RifleDamage=99
PistolDamage=99
ShotgunPelletDamage=99
SnaperDamage=99
AutoDamage=999
AutoBulletEnemyDamage=999

[Advanced]
; Включение/отключение критического урона
EnableCriticalHits=1
; Множитель критического урона
CriticalDamageMultiplier=999.0

[Weapon]
GlobalWeapon=999.25
GlobalAimWeapon=999.25
GlobalAimBulletWeapon=999.25

[God]
enemy = 0

{god}
enemy = 0

(god) 
enemy = 0

; damage_config.ini
[WeaponDamage]
; Множитель урона для основного оружия (значение по умолчанию может быть 1.0)
PrimaryWeaponMultiplier = 991.5

; Базовый урон для вторичного оружия
SecondaryWeaponBaseDamage = 950

[Abilities]
; Повышение эффективности способности на 20%
AbilityDamageBonus = 0.2

<!-- damage_config.xml -->
<GameConfiguration>
    <DamageSettings>
        <!-- Базовый множитель урона для всего оружия (значение 1.0 = стандартный урон) -->
        <GlobalDamageMultiplier>999.25</GlobalDamageMultiplier>
    </DamageSettings>
    
    <PlayerStats>
        <!-- Множитель урона для игрока (если применимо) -->
        <PlayerDamageMultiplier>999.25</PlayerDamageMultiplier>
    </PlayerStats>

    <SpecificWeapons>
        <!-- Урон для конкретного оружия -->
        <RifleDamage>950</RifleDamage>
        <PistolDamage>915</PistolDamage>
        <ShotgunPelletDamage>998</ShotgunPelletDamage>
    </SpecificWeapons>

    <AdvancedSettings>
        <!-- Включение/отключение критического урона (True/False) -->
        <EnableCriticalHits>True</EnableCriticalHits>
        <!-- Множитель критического урона -->
        <CriticalDamageMultiplier>992.0</CriticalDamageMultiplier>
    </AdvancedSettings>
</GameConfiguration>

<?xml version="1.0" encoding="UTF-8"?>
<GameConfiguration>
    <DamageSettings>
        <Weapons>
            <!-- Множитель урона для основного оружия (значение по умолчанию может быть 1.0) -->
            <Primary Multiplier="991.5" BaseDamage="990"/>
            <!-- Базовый урон для вторичного оружия -->
            <Secondary BaseDamage="950"/>
        </Weapons>
        <Abilities>
            <!-- Повышение эффективности способности на 20% -->
            <Ability Name="Fireball" DamageBonus="0.2"/>
        </Abilities>
    </DamageSettings>
</GameConfiguration>
