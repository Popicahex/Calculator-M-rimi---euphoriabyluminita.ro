# Calculator-Marimi---euphoriabyluminita.ro
Calculatorul de mărimi folosit pe site-ul euphoriabyluminita.ro

Descriere
Acest proiect oferă un calculator interactiv de mărimi, utilizat pe site-ul euphoriabyluminita.ro, care ajută vizitatorii să-și găsească mărimea potrivită pentru haine, pe baza înălțimii, greutății și sexului. Calculatorul folosește formula BMI pentru a recomanda mărimea corespunzătoare, afișând atât mărimea litere (XS, S, M, L, XL, XXL, XXXL), cât și mărimea numerică europeană.

Funcționalități principale
Introducerea datelor: înălțime (cm), greutate (kg) și sex (femeie/bărbat).

Validare pentru intervale admise:

Înălțime: 130 - 220 cm

Greutate: 35 - 160 kg

Calcul automat al indicelui de masă corporală (BMI).

Recomandarea mărimii potrivite în funcție de BMI și sex.

Afișarea unui indicator vizual pe o bară cu mărimile.

Ghid de mărimi general cu măsurători bust, talie și șold.

Design responsive și animat, ușor de integrat în orice site.

Cum se folosește
Apasă butonul Găsește-mi Mărimea 📏 pentru a deschide calculatorul.
![image](https://github.com/user-attachments/assets/8a54cbef-ecc7-4604-a526-43d39d8d3339)
Completează înălțimea și greutatea în câmpurile numerice.
![image](https://github.com/user-attachments/assets/77c800c8-57f9-4ded-aa17-006313a7a1d6)

Selectează sexul (Femeie sau Bărbat).

Apasă butonul Calculează Mărimea.

Vei primi recomandarea mărimii potrivite, afișată atât text, cât și vizual pe bara de mărimi.
![image](https://github.com/user-attachments/assets/e42e45ce-bd3e-451e-94b3-2158aa9b3db1)

Consultă ghidul general de mărimi pentru detalii suplimentare.
![image](https://github.com/user-attachments/assets/9ec0505c-8e14-48b7-bd9a-2aeea5f223ec)

Instalare și integrare
Acest calculator poate fi integrat direct în orice pagină HTML prin copierea următoarelor părți:

Codul HTML (containerul și formularul)

Stilurile CSS incluse în <style>

Scriptul JavaScript pentru logica calculatorului

Exemplu minimal de integrare:
<!-- Include codul HTML din proiect -->

<style>
  /* Include stilurile CSS din proiect */
</style>

<script>
  // Include codul JavaScript din proiect
</script>

Personalizare
Culorile și dimensiunile pot fi modificate în secțiunea CSS.

Intervalele de validare în JavaScript pot fi adaptate dacă este necesar.

Formula de calcul și criteriile de mărimi pot fi ajustate în funcție de specificațiile brandului.

Structura codului
HTML: definește formularul și elementele vizuale (buton, inputuri, tabel ghid mărimi).

CSS: stilizează interfața pentru un aspect modern, prietenos și responsive.

JavaScript: gestionează interacțiunea utilizatorului, validarea, calculul BMI și afișarea rezultatului.

Exemple de mărimi recomandate
| Litere | Numeric (EU) | Bust (cm) | Talie (cm) | Șold (cm) |
| ------ | ------------ | --------- | ---------- | --------- |
| XS     | 30–32        | 76–80     | 58–62      | 84–88     |
| S      | 34–36        | 82–86     | 64–68      | 88–92     |
| M      | 36–38        | 86–92     | 68–74      | 92–98     |
| L      | 38–40        | 92–98     | 74–80      | 98–104    |
| XL     | 40–42        | 98–104    | 80–88      | 104–110   |
| XXL    | 42–44        | 104–110   | 88–96      | 110–116   |
| XXXL   | 44–46        | 110–116   | 96–104     | 116–122   |


