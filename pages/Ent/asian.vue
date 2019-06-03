<template>
<section main>
  <b-container>
    <h1 class="title-color">Asian Movies showing today @ east London cinemas </h1>
    <br>
    <h2>Wednesday 5 June 2019</h2>

  <b-card-group deck
  class="mb-3 ">
    <StudentC /><!--Student of the year 2 -->
    <Blank />
    <Blank />
    </b-card-group>

    <!--Asian movies-->
    <!--<GallanC />--Dil Diyan Gallan -->
    <!--<BlackiaC />--Blackia-->
    <!--<KalankC />--Kalank-->

    <!--<MaharshiC />--Maharshi-->




      <!--<Airaa Airaa -->
      <!--<Badla ---Badia -->
      <!--<Border --Border -->
      <!--<Gully --Gully Boy -->
      <!--<Band /--Band Vaaje-->
      <!--<BealeC --If Beale Street Could talk-->

      <!--Black --Blackklansman -->
      <!--<BoyC /--Beautiful Boy -->

      <!--Burning --Burning-->
      <!--<Caper />--Capernaum -->

      <!--<Dragon --Dragon Ball Super -->
      <!--<EscapeC --Escape Room -->

      <!--<EverybodyC />--Everybody Knows -->
      <!--<GlassC --Glass-->
      <!--<GreenC /--Green Book-->

      <!--<Guddiyan />--Guddiyan Patole -->

      <!--<HappyC />--Happy Death Day -->
      <!--<Fight --The Fight-->
      <!--<Hannah --Hannah-->

      <!--<Kesari /--Kesari -->
      <!--<KanchanaC />--Kanchana 3 -->
      <!--<KavaludaariC />--Kavaludaari -->

      <!--<Kobiety --Kobiety Mafii 2 -->
      <!--kodathi --Kodathi Samaksham Balan Vakkeel-->
      <!--Kumbalangi --Kumbalangi Nights-->
      <!--<Junglee /--Junglee -->
    <!--<Luka /--Luka Chuppi  -->
    <!--<Lucifer /--Lucifer-->

      <!--<Bala --Miss Bala-->
      <!--<ManjeC />--Manje Bistre 2-->

      <!--Maiden --Maiden-->
      <!--<Milan -Milan Talkies-->
        <!--<NadhooC />--Nadhoo Khan -->
        <!--<PremakadhaC />--Oru Yamandan Premakadha-->

      <!--<Notebook />--Notebook-->
      <!--<Prodigy --The Prodigy-->
      <!--<Rabb /--Rabb Da Radio-->
      <!--<Ralph --Ralph Breaks The Internet: Wreck-It -->
        <!--<RomeoC --Romeo Akbar Walter-->

      <!--<Ring --Ring-->
      <!--Serenityx--Serenity -->
      <!--<SuperC /--Super Deluxe -->
      <!--<SherdilC /--SherDil-->

      <!--<Total /><-Total Dhamal  -->
  <!--<ScotsC />--Mary Queen Of Scots -->
      <!--<Kala /> Kala Shah Kala -->
      <!--Grinch --Grinch-->
      <!--<VanishingC --The Vanishing-->
      <!--<Vice />--Vice-->
      <!--<Crow --The White Crow-->

      </b-container>
      </section>

</template>

<script>

import FavouriteC from '@/components/Films/Favourite/FavouriteC'
import Mule from '@/components/Films/Mule'
import Vice from '@/components/Films/Vice'
import Blank from '@/components/Films/Blank'
import Ralph from '@/components/Films/Ralph'
import Spider from '@/components/Films/Spider'
import Destroyer from '@/components/Films/Destroyer'
import Preview from '@/components/Films/Preview'
import Creed from '@/components/Films/Creed'
import Colette from '@/components/Films/Colette'
import Lego from '@/components/Films/Lego'
import True from '@/components/Films/True'
import Caper from '@/components/Films/Caper'
import Black from '@/components/Films/Black'
import War from '@/components/Films/War'
import Aftermath from '@/components/Films/Aftermath'
import Serenityx from '@/components/Films/Serenityx'
import Gully from '@/components/Films/Gully'
import Kala from '@/components/Films/Kala'
import Ml from '@/components/Films/Ml'
import Luka from '@/components/Films/Luka'
import Badla from '@/components/Films/Badla'
import Border from '@/components/Films/Border'
import Bala from '@/components/Films/Bala'
import Guddiyan from '@/components/Films/Guddiyan'
import Kumbalangi from '@/components/Films/Kumbalangi'
import Total from '@/components/Films/Total'
import Bell from '@/components/Films/Bell'
import Kobiety from '@/components/Films/Kobiety'
import Kodathi from '@/components/Films/Kodathi'
import Maiden from '@/components/Films/Maiden'
import Fisherman from '@/components/Films/Fisherman'
import Fight from '@/components/Films/Fight'
import Prodigy from '@/components/Films/Prodigy'
import Band from '@/components/Films/Band'
import Milan from '@/components/Films/Milan'
import Burning from '@/components/Films/Burning'
import Ring from '@/components/Films/Ring'
import Hannah from '@/components/Films/Hannah'
import Rose from '@/components/Films/Rose'
import Crow from '@/components/Films/Crow'
import Junglee from '@/components/Films/Junglee'
import Lion from '@/components/Films/Lion'
import BlueC from '@/components/Films/Blue/BlueC'
import Notebook from '@/components/Films/Notebook'
import Lords from '@/components/Films/Lords'
import Lucifer from '@/components/Films/Lucifer'
import Rabb from '@/components/Films/Rabb'
import Airaa from '@/components/Films/Airaa/Airaa'
import Vanishing from '@/components/Films/Vanishing/Vanishing'
import VanishingC from '@/components/Films/Vanishing/VanishingC'
import Scots from '@/components/Films/Scots/Scots'
import ScotsC from '@/components/Films/Scots/ScotsC'
import Forgive from '@/components/Films/Forgive/Forgive'
import Boy from '@/components/Films/Boy/Boy'
import BoyC from '@/components/Films/Boy/BoyC'
import Dog from '@/components/Films/Dog/Dog'
import DogC from '@/components/Films/Dog/DogC'
import Ben from '@/components/Films/Ben/Ben'
import Bohemian from '@/components/Films/Bohemian/Bohemian'
import Cold from '@/components/Films/Cold/Cold'
import BealeC from '@/components/Films/Beale/BealeC'
import Bumblebee from '@/components/Films/Bumblebee/Bumblebee'
import Alita from '@/components/Films/Alita/Alita'
import AlitaC from '@/components/Films/Alita/AlitaC'
import Marvel from '@/components/Films/Marvel/Marvel'
import MarvelC from '@/components/Films/Marvel/MarvelC'
import Happy from '@/components/Films/Happy/Happy'
import HappyC from '@/components/Films/Happy/HappyC'
import Green from '@/components/Films/Green/Green'
import GreenC from '@/components/Films/Green/GreenC'
import Glass from '@/components/Films/Glass/Glass'
import GlassC from '@/components/Films/Glass/GlassC'
import Five from '@/components/Films/Five/Five'
import FiveC from '@/components/Films/Five/FiveC'
import Fighting from '@/components/Films/Fighting/Fighting'
import FightingC from '@/components/Films/Fighting/FightingC'
import Family from '@/components/Films/Family/Family'
import FamilyC from '@/components/Films/Family/FamilyC'
import Everybody from '@/components/Films/Everybody/Everybody'
import EverybodyC from '@/components/Films/Everybody/EverybodyC'
import Escape from '@/components/Films/Escape/Escape'
import EscapeC from '@/components/Films/Escape/EscapeC'
import Dragonworld from '@/components/Films/Dragonworld/Dragonworld'
import DragonworldC from '@/components/Films/Dragonworld/DragonworldC'
import Missing from '@/components/Films/Missing/Missing'
import MissingC from '@/components/Films/Missing/MissingC'
import Peppa from '@/components/Films/Peppa/Peppa'
import ShazamC from '@/components/Films/Shazam/ShazamC'
import PetC from '@/components/Films/Pet/PetC'
import KingC from '@/components/Films/King/KingC'
import KeeperC from '@/components/Films/Keeper/KeeperC'
import SisterC from '@/components/Films/Sister/SisterC'
import WonderC from '@/components/Films/Wonder/WonderC'
import UsC from '@/components/Films/Us/UsC'
import HellboyC from '@/components/Films/Hellboy/HellboyC'
import LittleC from '@/components/Films/Little/LittleC'
import PoppinsC from '@/components/Films/Poppins/PoppinsC'
import RomeoC from '@/components/Films/Romeo/RomeoC'
import ManjeC from '@/components/Films/Manje/ManjeC'
import SherdilC from '@/components/Films/Sherdil/SherdilC'
import SuperC from '@/components/Films/Super/SuperC'
import MidC from '@/components/Films/Mid/MidC'
import Kesari from '@/components/Films/Kesari'
import KalankC from '@/components/Films/Kalank/KalankC'
import KanchanaC from '@/components/Films/Kanchana/KanchanaC'
import NadhooC from '@/components/Films/Nadhoo/NadhooC'
import BlackiaC from '@/components/Films/Blackia/BlackiaC'
import KavaludaariC from '@/components/Films/Kavaludaari/KavaludaariC'
import GallanC from '@/components/Films/Gallan/GallanC'
import MaharshiC from '@/components/Films/Maharshi/MaharshiC'
import PremakadhaC from '@/components/Films/Premakadha/PremakadhaC'
import StudentC from '@/components/Films/Student/StudentC'









export default {
  head () {
    return {
      titleTemplate: '%s Asian Movies Today',
      meta         : [
        { hid: 'description', name: 'description', content: ' Whats on today @ cineworld, odeon, picturehouses, showcase & Vue cinemas in east London, Bexleyheath, Greenwich 02, Ilford,romford, South Woodford and West India Quay, June 2019 and free to watch online movies' }
      ]
    }
  },
  components: {
    Aftermath,
    Airaa,
    Alita,
    AlitaC,
    Badla,
    Bala,
    Band,
    BealeC,
    Bell,
    Ben,
    Black,
    Blank,
    BlackiaC,
    BlueC,
    Bohemian,
    Border,
    Boy,
    BoyC,
    Bumblebee,
    Burning,
    Caper,
    Cold,
    Colette,
    Creed,
    Crow,
    Destroyer,
    Dog,
    DogC,
    Dragonworld,
    DragonworldC,
    Escape,
    EscapeC,
    Everybody,
    EverybodyC,
    Family,
    FamilyC,
    FavouriteC,
    Fight,
    Fighting,
    FightingC,
    Fisherman,
    Five,
    FiveC,
    Forgive,
    GallanC,
    Glass,
    GlassC,
    Green,
    GreenC,
    Guddiyan,
    Gully,
    Hannah,
    Happy,
    HappyC,
    HellboyC,
    Kala,
    KalankC,
    KanchanaC,
    KavaludaariC,
    KeeperC,
    Kesari,
    KingC,
    Kobiety,
    Kodathi,
    Kumbalangi,
    Lego,
    LittleC,
    Lucifer,
    Lords,
    Luka,
    Maiden,
    ManjeC,
    MaharshiC,
    Marvel,
    MarvelC,
    MidC,
    Milan,
    Missing,
    MissingC,
    Ml,
    Mule,
    NadhooC,
    Notebook,
    Peppa,
    PetC,
    PoppinsC,
    PremakadhaC,
    Preview,
    Prodigy,
    Rabb,
    Ralph,
    Ring,
    RomeoC,
    Rose,
    Scots,
    ScotsC,
    Serenityx,
    ShazamC,
    SherdilC,
    SisterC,
    Spider,
    StudentC,
    SuperC,
    Total,
    True,
    Vanishing,
    VanishingC,
    Vice,
    War,
    Junglee,
    Lion,
    UsC,
    WonderC,
      }
}
</script>
