# Käyttöliittymän rakenne (Harjoitus 24)

Tämä on **Windows Forms -harjoitusprojekti**, jossa voidaan piirtää eri muotoja (suorakulmio, neliö, kolmio, ympyrä) ja laskea niiden pinta-ala.

## Toiminnot
- Käyttäjä voi valita piirrettävän muodon pudotusvalikosta (ComboBox).
- Käyttäjä antaa leveys- ja korkeus-arvot (tai säteen ympyrälle).
- Ohjelma laskee pinta-alan ja näyttää sen käyttöliittymässä.
- Piirtoalue (Panel) näyttää valitun muodon mittasuhteiden mukaan.
- Käyttäjä voi tyhjentää kentät ja aloittaa alusta.

## Teknologiat
- C# (.NET Windows Forms)
- GDI+ (piirtämiseen `Graphics`-luokan avulla)
- Git + GitHub versionhallintaan

## Projektin rakenne
- `KayttoliittymanForm.cs` – pääikkunan logiikka
- `KayttoliittymanForm.Designer.cs` – lomakkeen komponentit
- `Program.cs` – sovelluksen käynnistyspiste

## Käyttöönotto
1. Kloonaa tämä repo:
   ```bash
   git clone https://github.com/USERNAME/kayttoliittyman-rakenne.git
