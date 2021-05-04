# Live koding (i underkant av 10 minutter)


JS-fiddle:
#### 1. [Hva er en variabel?](https://jsfiddle.net/matsjoer/skunyf3p/)

<details>
  <summary>Fasit</summary>
  
  ```
  var boks = 2;
  var navn = "mats";
  ```
</details>

#### 2. [Hvordan endrer vi verdien til en variabel?](https://jsfiddle.net/matsjoer/8hwcx9om/)

<details>
  <summary>Fasit</summary>
  
  ```
  var a = 3;

  skrivUt(a);

  // Vis hvordan man kan forandre verdien til variabler

  a++;

  skrivUt(a);
  ```
</details>

#### 3. [Hva kan vi bruke variabler til?](https://jsfiddle.net/matsjoer/xdypLbj3/)

<details>
  <summary>Fasit</summary>
  
  ```
  var alder = 67;

  // Vis en en valgsetning

  if (alder >= 67) {
    skrivUt('Forever young');
  } else if (alder >= 18) {
    skrivUt('Tia flyg ass');
  } else {
    skrivUt('Still in school');
  }
  ```
</details>

#### 4. [Hvordan kan jeg unngå å skrive så mye?](https://jsfiddle.net/matsjoer/nh0e3rkc/)

<details>
  <summary>Fasit</summary>
  
  ```
  var mats = 28;
  var perEgil = 70;
  var larsPetter = 10;

  // Vis en funksjon

  function sjekkAlder(alder) {
    if (alder >= 67) {
      skrivUt('Forever young');
    } else if (alder >= 18) {
      skrivUt('Tia flyg ass');
    } else {
      skrivUt('Still in school');
    }
  }

  sjekkAlder(mats);
  sjekkAlder(perEgil);
  sjekkAlder(larsPetter);
  ```
</details>
