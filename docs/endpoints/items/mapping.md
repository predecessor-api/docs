# Item Mapping

```
{baseURL}/item-mapping/
```

Returns the ItemID -> ItemName mapping.

**Note: Not yet implemented**

We do have a JSON string that was shared in the Predecessor Discord's `#public-api` channel, though, as an array of objects.

There's also a hand-curated key:value JSON string as an object of just ItemID -> ItemName.

<details>
  <summary>Show JSON (array of object, official from Discord)</summary>

```json
[
  {
    "item_name": "Malediction",
    "item_id": "200606",
    "item_description": "Anti-Physical"
  },
  {
    "item_name": "Brutallax",
    "item_id": "200303",
    "item_description": "Remove Disables"
  },
  {
    "item_name": "StrengthTonic",
    "item_id": "100010",
    "item_description": ""
  },
  {
    "item_name": "StaminaTonic",
    "item_id": "100008",
    "item_description": ""
  },
  {
    "item_name": "ProtectionTonic",
    "item_id": "100005",
    "item_description": ""
  },
  {
    "item_name": "IntellectTonic",
    "item_id": "100003",
    "item_description": ""
  },
  {
    "item_name": "RefillablePotion",
    "item_id": "100006",
    "item_description": ""
  },
  {
    "item_name": "Hunt",
    "item_id": "300005",
    "item_description": ""
  },
  {
    "item_name": "ConsortCrest",
    "item_id": "200601",
    "item_description": "Deal Damage when Near Allies to earn gold and evolve into "
  },
  {
    "item_name": "RogueCrest",
    "item_id": "200201",
    "item_description": "Land Abilities and Kill Enemies to evolve into "
  },
  {
    "item_name": "AssassinCrest",
    "item_id": "200202",
    "item_description": ""
  },
  {
    "item_name": "MarksmanCrest",
    "item_id": "200101",
    "item_description": "Land Basic Attacks and Kill Enemies to evolve into "
  },
  {
    "item_name": "SharpshooterCrest",
    "item_id": "200102",
    "item_description": ""
  },
  {
    "item_name": "WarriorCrest",
    "item_id": "200301",
    "item_description": "Deal Damage and Kill Enemies to evolve into "
  },
  {
    "item_name": "ChampionCrest",
    "item_id": "200302",
    "item_description": ""
  },
  {
    "item_name": "MagicianCrest",
    "item_id": "200401",
    "item_description": "Land Abilities and Kill Enemies to evolve into "
  },
  {
    "item_name": "OccultCrest",
    "item_id": "200402",
    "item_description": "Land Abilities and Kill Enemies to evolve into "
  },
  {
    "item_name": "WarlockCrest",
    "item_id": "200404",
    "item_description": ""
  },
  {
    "item_name": "GuardianCrest",
    "item_id": "200602",
    "item_description": "Deal Damage when Near Allies to earn gold and evolve into "
  },
  {
    "item_name": "WizardCrest",
    "item_id": "200403",
    "item_description": ""
  },
  {
    "item_name": "KeeperCrest",
    "item_id": "200603",
    "item_description": ""
  },
  {
    "item_name": "TitanCrest",
    "item_id": "200501",
    "item_description": "Receive Damage and Kill Enemies to evolve into "
  },
  {
    "item_name": "WardenCrest",
    "item_id": "200604",
    "item_description": ""
  },
  {
    "item_name": "GoliathCrest",
    "item_id": "200502",
    "item_description": ""
  },
  {
    "item_name": "WildHunt",
    "item_id": "300005",
    "item_description": ""
  },
  {
    "item_name": "Solstone",
    "item_id": "400601",
    "item_description": ""
  },
  {
    "item_name": "StealthWard",
    "item_id": "100009",
    "item_description": ""
  },
  {
    "item_name": "Sentry",
    "item_id": "100007",
    "item_description": ""
  },
  {
    "item_name": "Epoch",
    "item_id": "200405",
    "item_description": "Survive Burst"
  },
  {
    "item_name": "Obelisk",
    "item_id": "200406",
    "item_description": "Enhances Basics"
  },
  {
    "item_name": "Soulbearer",
    "item_id": "200407",
    "item_description": "Survive Burst"
  },
  {
    "item_name": "Tempest",
    "item_id": "200408",
    "item_description": "Area Damage"
  },
  {
    "item_name": "RiftWalkers",
    "item_id": "200607",
    "item_description": "Initiation"
  },
  {
    "item_name": "Codex",
    "item_id": "300001",
    "item_description": ""
  },
  {
    "item_name": "ChronomaticWand",
    "item_id": "400008",
    "item_description": ""
  },
  {
    "item_name": "SpiritBeads",
    "item_id": "300014",
    "item_description": ""
  },
  {
    "item_name": "DuskStave",
    "item_id": "400014",
    "item_description": ""
  },
  {
    "item_name": "AstralCatalyst",
    "item_id": "500401",
    "item_description": ""
  },
  {
    "item_name": "PotentStaff",
    "item_id": "300009",
    "item_description": ""
  },
  {
    "item_name": "Scepter",
    "item_id": "300011",
    "item_description": ""
  },
  {
    "item_name": "ScaldingSceptre",
    "item_id": "400030",
    "item_description": ""
  },
  {
    "item_name": "Caustica",
    "item_id": "500403",
    "item_description": ""
  },
  {
    "item_name": "DiffusalCane",
    "item_id": "400012",
    "item_description": ""
  },
  {
    "item_name": "Combustion",
    "item_id": "500404",
    "item_description": ""
  },
  {
    "item_name": "VitalityBeads",
    "item_id": "300016",
    "item_description": ""
  },
  {
    "item_name": "TenaciousDrape",
    "item_id": "400038",
    "item_description": ""
  },
  {
    "item_name": "Dreambinder",
    "item_id": "500405",
    "item_description": ""
  },
  {
    "item_name": "Megacosm",
    "item_id": "500409",
    "item_description": ""
  },
  {
    "item_name": "SpellSlasher",
    "item_id": "300013",
    "item_description": ""
  },
  {
    "item_name": "VioletBrooch",
    "item_id": "400039",
    "item_description": ""
  },
  {
    "item_name": "Oathkeeper",
    "item_id": "500410",
    "item_description": ""
  },
  {
    "item_name": "OblivionCrown",
    "item_id": "500411",
    "item_description": ""
  },
  {
    "item_name": "Wraps",
    "item_id": "300017",
    "item_description": ""
  },
  {
    "item_name": "NullifyingMask",
    "item_id": "400023",
    "item_description": ""
  },
  {
    "item_name": "Spellbreaker",
    "item_id": "500413",
    "item_description": ""
  },
  {
    "item_name": "SpikedBirch",
    "item_id": "400033",
    "item_description": ""
  },
  {
    "item_name": "TaintedScepter",
    "item_id": "500415",
    "item_description": ""
  },
  {
    "item_name": "VoidCrystal",
    "item_id": "400040",
    "item_description": ""
  },
  {
    "item_name": "WorldBreaker",
    "item_id": "500416",
    "item_description": ""
  },
  {
    "item_name": "WraithLeggings",
    "item_id": "500417",
    "item_description": ""
  },
  {
    "item_name": "Tunic",
    "item_id": "300015",
    "item_description": ""
  },
  {
    "item_name": "AbyssalBracers",
    "item_id": "400001",
    "item_description": ""
  },
  {
    "item_name": "GolemsGift",
    "item_id": "500418",
    "item_description": ""
  },
  {
    "item_name": "IceskornTalons",
    "item_id": "200305",
    "item_description": "Dueling"
  },
  {
    "item_name": "Sabre",
    "item_id": "300010",
    "item_description": ""
  },
  {
    "item_name": "Shortsword",
    "item_id": "300012",
    "item_description": ""
  },
  {
    "item_name": "RuthlessBroadsword",
    "item_id": "400028",
    "item_description": ""
  },
  {
    "item_name": "Basilisk",
    "item_id": "500302",
    "item_description": ""
  },
  {
    "item_name": "FortifiedMantle",
    "item_id": "400016",
    "item_description": ""
  },
  {
    "item_name": "Citadel",
    "item_id": "500516",
    "item_description": ""
  },
  {
    "item_name": "TemporalRipper",
    "item_id": "400037",
    "item_description": ""
  },
  {
    "item_name": "Draconum",
    "item_id": "500304",
    "item_description": ""
  },
  {
    "item_name": "BarbedPauldron",
    "item_id": "400004",
    "item_description": ""
  },
  {
    "item_name": "CeruleanStone",
    "item_id": "400017",
    "item_description": ""
  },
  {
    "item_name": "Frostguard",
    "item_id": "500505",
    "item_description": ""
  },
  {
    "item_name": "HeroicGuard",
    "item_id": "400019",
    "item_description": ""
  },
  {
    "item_name": "Legacy",
    "item_id": "500306",
    "item_description": ""
  },
  {
    "item_name": "BloodTome",
    "item_id": "400005",
    "item_description": ""
  },
  {
    "item_name": "Lifebinder",
    "item_id": "500407",
    "item_description": ""
  },
  {
    "item_name": "Bloodlust",
    "item_id": "400042",
    "item_description": ""
  },
  {
    "item_name": "Mutilator",
    "item_id": "500307",
    "item_description": ""
  },
  {
    "item_name": "Longbow",
    "item_id": "300007",
    "item_description": ""
  },
  {
    "item_name": "CompositeBow",
    "item_id": "400010",
    "item_description": ""
  },
  {
    "item_name": "Prophecy",
    "item_id": "500412",
    "item_description": ""
  },
  {
    "item_name": "EnergyStream",
    "item_id": "300003",
    "item_description": ""
  },
  {
    "item_name": "DivineWreath",
    "item_id": "400013",
    "item_description": ""
  },
  {
    "item_name": "HallowedBraid",
    "item_id": "400018",
    "item_description": ""
  },
  {
    "item_name": "Requiem",
    "item_id": "500607",
    "item_description": ""
  },
  {
    "item_name": "Greatsword",
    "item_id": "300004",
    "item_description": ""
  },
  {
    "item_name": "BandedEmerald",
    "item_id": "400002",
    "item_description": ""
  },
  {
    "item_name": "Salvation",
    "item_id": "500310",
    "item_description": ""
  },
  {
    "item_name": "SerratedBlade",
    "item_id": "400031",
    "item_description": ""
  },
  {
    "item_name": "TaintedBlade",
    "item_id": "300308",
    "item_description": ""
  },
  {
    "item_name": "EssenceRing",
    "item_id": "400015",
    "item_description": ""
  },
  {
    "item_name": "Timewarp",
    "item_id": "500608",
    "item_description": ""
  },
  {
    "item_name": "Vanguardian",
    "item_id": "500610",
    "item_description": ""
  },
  {
    "item_name": "SteelMail",
    "item_id": "400035",
    "item_description": ""
  },
  {
    "item_name": "WardensFaith",
    "item_id": "500515",
    "item_description": ""
  },
  {
    "item_name": "TimeFluxBand",
    "item_id": "200409",
    "item_description": "Time Travel"
  },
  {
    "item_name": "Typhoon",
    "item_id": "200410",
    "item_description": "Mobility"
  },
  {
    "item_name": "Leafsong",
    "item_id": "200605",
    "item_description": "Enhance Mobility"
  },
  {
    "item_name": "AlchemicalRod",
    "item_id": "400027",
    "item_description": ""
  },
  {
    "item_name": "AzureCore",
    "item_id": "500402",
    "item_description": ""
  },
  {
    "item_name": "Dynamo",
    "item_id": "500502",
    "item_description": ""
  },
  {
    "item_name": "Elafrost",
    "item_id": "500603",
    "item_description": ""
  },
  {
    "item_name": "PolarTreads",
    "item_id": "400024",
    "item_description": ""
  },
  {
    "item_name": "GalaxyGreaves",
    "item_id": "500506",
    "item_description": ""
  },
  {
    "item_name": "HexboundBracers",
    "item_id": "500508",
    "item_description": ""
  },
  {
    "item_name": "ChaoticCore",
    "item_id": "400007",
    "item_description": ""
  },
  {
    "item_name": "RuneBow",
    "item_id": "400042",
    "item_description": ""
  },
  {
    "item_name": "Magnify",
    "item_id": "500408",
    "item_description": ""
  },
  {
    "item_name": "Ortus",
    "item_id": "200204",
    "item_description": "Multi-kill"
  },
  {
    "item_name": "Pacifier",
    "item_id": "200105",
    "item_description": "Mobility"
  },
  {
    "item_name": "Crossbow",
    "item_id": "300002",
    "item_description": ""
  },
  {
    "item_name": "ZealousTomahawk",
    "item_id": "400041",
    "item_description": ""
  },
  {
    "item_name": "Ashbringer",
    "item_id": "500101",
    "item_description": ""
  },
  {
    "item_name": "HonedKris",
    "item_id": "400020",
    "item_description": ""
  },
  {
    "item_name": "Malady",
    "item_id": "500201",
    "item_description": ""
  },
  {
    "item_name": "DemonEdge",
    "item_id": "500202",
    "item_description": ""
  },
  {
    "item_name": "Mesmer",
    "item_id": "500203",
    "item_description": ""
  },
  {
    "item_name": "Deathstalker",
    "item_id": "500204",
    "item_description": ""
  },
  {
    "item_name": "Imperator",
    "item_id": "500104",
    "item_description": ""
  },
  {
    "item_name": "Dread",
    "item_id": "500205",
    "item_description": ""
  },
  {
    "item_name": "IronwoodWarbow",
    "item_id": "400022",
    "item_description": ""
  },
  {
    "item_name": "RobustArbalest",
    "item_id": "400026",
    "item_description": ""
  },
  {
    "item_name": "LightningHawk",
    "item_id": "500106",
    "item_description": ""
  },
  {
    "item_name": "Viper",
    "item_id": "500108",
    "item_description": ""
  },
  {
    "item_name": "Omen",
    "item_id": "500208",
    "item_description": ""
  },
  {
    "item_name": "Absolution",
    "item_id": "500110",
    "item_description": ""
  },
  {
    "item_name": "RavenousRapier",
    "item_id": "400025",
    "item_description": ""
  },
  {
    "item_name": "SkySplitter",
    "item_id": "500111",
    "item_description": ""
  },
  {
    "item_name": "StormBreaker",
    "item_id": "500112",
    "item_description": ""
  },
  {
    "item_name": "TaintedRounds",
    "item_id": "500113",
    "item_description": ""
  },
  {
    "item_name": "ThePerforator",
    "item_id": "500210",
    "item_description": ""
  },
  {
    "item_name": "Vanquisher",
    "item_id": "500211",
    "item_description": ""
  },
  {
    "item_name": "Nex",
    "item_id": "200203",
    "item_description": "Burst Damage"
  },
  {
    "item_name": "Witchstalker",
    "item_id": "200205",
    "item_description": "Remove Disables"
  },
  {
    "item_name": "Breach",
    "item_id": "500102",
    "item_description": ""
  },
  {
    "item_name": "TectonicMallet",
    "item_id": "500507",
    "item_description": ""
  },
  {
    "item_name": "BarbaricCleaver",
    "item_id": "400003",
    "item_description": ""
  },
  {
    "item_name": "Mindrazor",
    "item_id": "500206",
    "item_description": ""
  },
  {
    "item_name": "Nightfall",
    "item_id": "500207",
    "item_description": ""
  },
  {
    "item_name": "Painweaver",
    "item_id": "500209",
    "item_description": ""
  },
  {
    "item_name": "Silentium",
    "item_id": "200609",
    "item_description": "Anti-Magical"
  },
  {
    "item_name": "Marshal",
    "item_id": "500605",
    "item_description": ""
  },
  {
    "item_name": "TruesilverBracelet",
    "item_id": "500609",
    "item_description": ""
  },
  {
    "item_name": "Augmentation",
    "item_id": "500301",
    "item_description": ""
  },
  {
    "item_name": "Claymore",
    "item_id": "400009",
    "item_description": ""
  },
  {
    "item_name": "Bonesaw",
    "item_id": "500303",
    "item_description": ""
  },
  {
    "item_name": "CrystallineCuirass",
    "item_id": "500501",
    "item_description": ""
  },
  {
    "item_name": "Brimstone",
    "item_id": "400006",
    "item_description": ""
  },
  {
    "item_name": "FireBlossom",
    "item_id": "500503",
    "item_description": ""
  },
  {
    "item_name": "FluxMatrix",
    "item_id": "500504",
    "item_description": ""
  },
  {
    "item_name": "Infernum",
    "item_id": "500305",
    "item_description": ""
  },
  {
    "item_name": "Overlord",
    "item_id": "500309",
    "item_description": ""
  },
  {
    "item_name": "LifeStream",
    "item_id": "300006",
    "item_description": ""
  },
  {
    "item_name": "StalwartGauntlets",
    "item_id": "400034",
    "item_description": ""
  },
  {
    "item_name": "RaimentOfRenewal",
    "item_id": "500511",
    "item_description": ""
  },
  {
    "item_name": "Stonewall",
    "item_id": "500512",
    "item_description": ""
  },
  {
    "item_name": "HornedPlate",
    "item_id": "400021",
    "item_description": ""
  },
  {
    "item_name": "TaintedGuard",
    "item_id": "500510",
    "item_description": ""
  },
  {
    "item_name": "VoidHelm",
    "item_id": "500514",
    "item_description": ""
  },
  {
    "item_name": "UnbrokenWill",
    "item_id": "500513",
    "item_description": ""
  },
  {
    "item_name": "Liberator",
    "item_id": "200104",
    "item_description": "Remove Disables"
  },
  {
    "item_name": "DustDevil",
    "item_id": "500103",
    "item_description": ""
  },
  {
    "item_name": "CrimsonEdge",
    "item_id": "400011",
    "item_description": ""
  },
  {
    "item_name": "Terminus",
    "item_id": "500114",
    "item_description": ""
  },
  {
    "item_name": "Demolisher",
    "item_id": "500115",
    "item_description": ""
  },
  {
    "item_name": "Kingsbane",
    "item_id": "500105",
    "item_description": ""
  },
  {
    "item_name": "Eviscerator",
    "item_id": "200103",
    "item_description": "Anti-Tank"
  },
  {
    "item_name": "Fenix",
    "item_id": "200304",
    "item_description": "Revive"
  },
  {
    "item_name": "NyrWarboots",
    "item_id": "200503",
    "item_description": "Initiation"
  },
  {
    "item_name": "SaphirsMantle",
    "item_id": "200505",
    "item_description": "Durability"
  },
  {
    "item_name": "Wellspring",
    "item_id": "500601",
    "item_description": ""
  },
  {
    "item_name": "TaintedTotem",
    "item_id": "500606",
    "item_description": ""
  },
  {
    "item_name": "SoulChalice",
    "item_id": "400032",
    "item_description": ""
  },
  {
    "item_name": "Reckoning",
    "item_id": "500109",
    "item_description": ""
  },
  {
    "item_name": "Tranquility",
    "item_id": "200610",
    "item_description": "Heal Allies"
  },
  {
    "item_name": "CrystalTear",
    "item_id": "500602",
    "item_description": ""
  },
  {
    "item_name": "Razorback",
    "item_id": "200504",
    "item_description": "Reflect Damage"
  },
  {
    "item_name": "LochShawl",
    "item_id": "400036",
    "item_description": ""
  },
  {
    "item_name": "Leviathan",
    "item_id": "500509",
    "item_description": ""
  },
  {
    "item_name": "Sanctification",
    "item_id": "200608",
    "item_description": "Survive Burst"
  }
]
```

</details>

<details>
  <summary>Show JSON (hand-curated key:value object)</summary>
<br/>
<strong>NOTE: This JSON omits two duplicate keys:</strong>

<ul>
  <li>"300005": "WildHunt", // duplicate ID with "Hunt"</li>
  <li>"400042": "RuneBow", // duplicate ID with "Bloodlust"</li>
</ul>

```json
{
  "100003": "IntellectTonic",
  "100005": "ProtectionTonic",
  "100006": "RefillablePotion",
  "100007": "Sentry",
  "100008": "StaminaTonic",
  "100009": "StealthWard",
  "100010": "StrengthTonic",
  "200101": "MarksmanCrest",
  "200102": "SharpshooterCrest",
  "200103": "Eviscerator",
  "200104": "Liberator",
  "200105": "Pacifier",
  "200201": "RogueCrest",
  "200202": "AssassinCrest",
  "200203": "Nex",
  "200204": "Ortus",
  "200205": "Witchstalker",
  "200301": "WarriorCrest",
  "200302": "ChampionCrest",
  "200303": "Brutallax",
  "200304": "Fenix",
  "200305": "IceskornTalons",
  "200401": "MagicianCrest",
  "200402": "OccultCrest",
  "200403": "WizardCrest",
  "200404": "WarlockCrest",
  "200405": "Epoch",
  "200406": "Obelisk",
  "200407": "Soulbearer",
  "200408": "Tempest",
  "200409": "TimeFluxBand",
  "200410": "Typhoon",
  "200501": "TitanCrest",
  "200502": "GoliathCrest",
  "200503": "NyrWarboots",
  "200504": "Razorback",
  "200505": "SaphirsMantle",
  "200601": "ConsortCrest",
  "200602": "GuardianCrest",
  "200603": "KeeperCrest",
  "200604": "WardenCrest",
  "200605": "Leafsong",
  "200606": "Malediction",
  "200607": "RiftWalkers",
  "200608": "Sanctification",
  "200609": "Silentium",
  "200610": "Tranquility",
  "300001": "Codex",
  "300002": "Crossbow",
  "300003": "EnergyStream",
  "300004": "Greatsword",
  "300005": "Hunt",
  "300006": "LifeStream",
  "300007": "Longbow",
  "300009": "PotentStaff",
  "300010": "Sabre",
  "300011": "Scepter",
  "300012": "Shortsword",
  "300013": "SpellSlasher",
  "300014": "SpiritBeads",
  "300015": "Tunic",
  "300016": "VitalityBeads",
  "300017": "Wraps",
  "300308": "TaintedBlade",
  "400001": "AbyssalBracers",
  "400002": "BandedEmerald",
  "400003": "BarbaricCleaver",
  "400004": "BarbedPauldron",
  "400005": "BloodTome",
  "400006": "Brimstone",
  "400007": "ChaoticCore",
  "400008": "ChronomaticWand",
  "400009": "Claymore",
  "400010": "CompositeBow",
  "400011": "CrimsonEdge",
  "400012": "DiffusalCane",
  "400013": "DivineWreath",
  "400014": "DuskStave",
  "400015": "EssenceRing",
  "400016": "FortifiedMantle",
  "400017": "CeruleanStone",
  "400018": "HallowedBraid",
  "400019": "HeroicGuard",
  "400020": "HonedKris",
  "400021": "HornedPlate",
  "400022": "IronwoodWarbow",
  "400023": "NullifyingMask",
  "400024": "PolarTreads",
  "400025": "RavenousRapier",
  "400026": "RobustArbalest",
  "400027": "AlchemicalRod",
  "400028": "RuthlessBroadsword",
  "400030": "ScaldingSceptre",
  "400031": "SerratedBlade",
  "400032": "SoulChalice",
  "400033": "SpikedBirch",
  "400034": "StalwartGauntlets",
  "400035": "SteelMail",
  "400036": "LochShawl",
  "400037": "TemporalRipper",
  "400038": "TenaciousDrape",
  "400039": "VioletBrooch",
  "400040": "VoidCrystal",
  "400041": "ZealousTomahawk",
  "400042": "Bloodlust",
  "400601": "Solstone",
  "500101": "Ashbringer",
  "500102": "Breach",
  "500103": "DustDevil",
  "500104": "Imperator",
  "500105": "Kingsbane",
  "500106": "LightningHawk",
  "500108": "Viper",
  "500109": "Reckoning",
  "500110": "Absolution",
  "500111": "SkySplitter",
  "500112": "StormBreaker",
  "500113": "TaintedRounds",
  "500114": "Terminus",
  "500115": "Demolisher",
  "500201": "Malady",
  "500202": "DemonEdge",
  "500203": "Mesmer",
  "500204": "Deathstalker",
  "500205": "Dread",
  "500206": "Mindrazor",
  "500207": "Nightfall",
  "500208": "Omen",
  "500209": "Painweaver",
  "500210": "ThePerforator",
  "500211": "Vanquisher",
  "500301": "Augmentation",
  "500302": "Basilisk",
  "500303": "Bonesaw",
  "500304": "Draconum",
  "500305": "Infernum",
  "500306": "Legacy",
  "500307": "Mutilator",
  "500309": "Overlord",
  "500310": "Salvation",
  "500401": "AstralCatalyst",
  "500402": "AzureCore",
  "500403": "Caustica",
  "500404": "Combustion",
  "500405": "Dreambinder",
  "500407": "Lifebinder",
  "500408": "Magnify",
  "500409": "Megacosm",
  "500410": "Oathkeeper",
  "500411": "OblivionCrown",
  "500412": "Prophecy",
  "500413": "Spellbreaker",
  "500415": "TaintedScepter",
  "500416": "WorldBreaker",
  "500417": "WraithLeggings",
  "500418": "GolemsGift",
  "500501": "CrystallineCuirass",
  "500502": "Dynamo",
  "500503": "FireBlossom",
  "500504": "FluxMatrix",
  "500505": "Frostguard",
  "500506": "GalaxyGreaves",
  "500507": "TectonicMallet",
  "500508": "HexboundBracers",
  "500509": "Leviathan",
  "500510": "TaintedGuard",
  "500511": "RaimentOfRenewal",
  "500512": "Stonewall",
  "500513": "UnbrokenWill",
  "500514": "VoidHelm",
  "500515": "WardensFaith",
  "500516": "Citadel",
  "500601": "Wellspring",
  "500602": "CrystalTear",
  "500603": "Elafrost",
  "500605": "Marshal",
  "500606": "TaintedTotem",
  "500607": "Requiem",
  "500608": "Timewarp",
  "500609": "TruesilverBracelet",
  "500610": "Vanguardian"
}
```

</details>
