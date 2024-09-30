<h1>Proiect de testare al site-ului web al Primăriei Techirghiol</h1>


MAI URMEAZĂ MODIFICĂRI (perioada: Septembrie-Octombrie-Noiembrie + perioadă de studii pentru ISTQB și recapitulări: August-Octombrie) 


Scopul proiectului final pentru „Cursul de testare manuală IT Factory” reprezintă utilizarea tuturor cunoștințelor asimilate de-a lungul sesiunilor de curs, și de a le putea aplica în mod practic.

Părți testate din site-ul web: https://www.primariatechirghiol.ro

Instrumente utilizate: Jira și Zephyr Squad.

<h2>Specificații funcționale:</h2>

Story-urile de mai jos au fost create în Jira și descriu unele specificații funcționale ale site-ului web al Primăriei Techirghiol, pentru care se realizează proiectul final:
![Screenshot (18836)](https://github.com/user-attachments/assets/dd41c737-50f0-497d-a5ea-cfc3494f6a20)

Aici puteți găsi versiunea care a fost creată pentru acest proiect:
![Screenshot (18841)](https://github.com/user-attachments/assets/cf0efd5d-01a2-44cb-b9f2-51ed45697818)

<h2>Procesul testării</h2>

Procesul de testare a fost operat pe baza procesului de testare standard, așa cum este descris mai jos.

<h3>1.1 Planificarea testării</h3>

Planul de testare este conceput pentru a descrie toate amănuntele testării.

Planul identifică elementele de testat, caracteristicile de testat, tipurile de testare care trebuie efectuate, personalul responsabil de testare, resursele și programul necesar pentru finalizarea testării și riscurile asociate cu planul. Planul de testare care a fost creat pentru acest proiect poate fi găsit aici:

[Plan de testare - Primăria Techirghiol.pdf](https://shorturl.at/CyqdA) 

<h4>1.1.1. Persoane alocate și roluri atribuite proiectului</h4>

<ul>
  <li>Csipas Valeriu - Project manager/Managerul proiectului</li> 
  <li>Moga Constantin - Product owner/Proprietarul produsului</li> 
  <li>Buga Ovidiu - Software developer/Dezvoltatorul software-ului</li> 
  <li>POKA NORBERT - Team Lead/Liderul Testării</li>  
  <li>Sabou Iulia - QA (Quality Assurance/Asiguratorul calității) 1</li> 
  <li>Talpoș Armand - QA 2</li> 
  <li>Oprișan Mugurel	- QA 3</li> 
</ul>

<h4>1.1.2 Criteriile de intrare definite</h4>
Criteriile de intrare în testare reprezintă următoarele:
<ul>
  <li>riscurile de proiect au fost identificate și moderate;</li> 
  <li>rolurile și responsabilitățile au fost alocate și agreate;</li> 
  <li>termenele limită au fost stabilite;</li> 
  <li>domeniul de aplicare a fost stabilit și comunicat membrilor echipei;</li> 
  <li>obiectivele testării au fost definite și transmise membrilor echipei.</li> 
</ul>

<h4>1.1.3 Criterii de ieșire definite</h4>
Iar criteriile de ieșire din testare sunt acestea:
<ul>
  <li>riscurile de produs au fost găsite și mitigate;</li> 
  <li>nu au rămas defecte critice deschise;</li> 
  <li>termenele limită au fost respectate;</li> 
  <li>cel puțin 85% din toate testele sunt trecute;</li> 
  <li>documentarea testării este finalizată și comunicată părților interesate/stakeholderilor (TCR este generat);</li> 
  <li>toate defectele sunt documentate și transmise părților interesate/stakeholderilor.</li> 
</ul>

<h4>1.1.4 Domeniul de testare</h4>

<h5>Teste în domeniul de aplicare:</h5>
<ul>
  <li>Testarea cerințelor funcționale, de performanță, de cazuri de utilizare;</li> 
  <li>Cerințe de calitate și metrici de potrivire primariatechirghiol.ro.</li> 
</ul>

<h5>Teste în afara domeniului de aplicare:</h5>
<ul>
  <li>Testarea cerințelor funcționale pentru sisteme din afara primariatechirghiol.ro;</li>
  <li>Testarea de securitate;</li>
  <li>Testarea planului de recuperare în caz de dezastru și de continuitate a afacerii;</li>
  <li>Testarea automată.</li>
</ul>

<h4>1.1.5 Riscuri detectate</h4>

<h5>Riscuri de produs:</h5>
Riscul asociat cu produsul final este cel imediat menționat:
<ul>
  <li>potențial pică pagina web dacă este încărcată cu exagerat de multe date.</li> 
</ul>

<h5>Riscuri de proiect:</h5>
În timp ce riscurile asociate proiectului sunt cele următoare:
<ul>
  <li>membrul echipei-QA 2 riscă să se infecteze cu virusul COVID-19 din cauza faptului că unde înoptează sunt persoane bolnave de COVID-19, și nu are posibilitatea de a petrece nopțile în altă locuință sau încăpere, ceea ce poate crește volumul de lucru al celorlalți membri ai echipei;</li>
  <li>membrul echipei-QA 3 nu are suficientă experiență pe parte de testare manuală pentru a finaliza de unul singur ceea ce are de făcut.</li>
</ul>

<h4>1.1.6 Evaluarea criteriilor de intrare</h4>

Criteriile de intrare definite în faza "Planificării testării" au fost atinse, procesul de testare putând continua.
  
<h3>1.2 Monitorizarea și controlul testării</h3>
Procesul de testare a fost monitorizat continuu, de la început până la sfârșit. A fost generat Raportul de status/Test status report pentru compararea eficientă a progresului de moment cu cel așteptat. Dacă devierile de plan au pus stăpânire peste întreaga desfășurare, atunci au fost luate măsuri de control. La fel s-a întâmplat și în cazul în care apărea riscul de a nu fi îndeplinite obiectivele la timp. Rolul acestei etape este de a crește calitatea și eficiența.

![Screenshot (18843)](https://github.com/user-attachments/assets/617e6d65-f8db-4cab-8f03-cec65f1f46a7)
![Screenshot (18844)](https://github.com/user-attachments/assets/d2fa457e-f48f-4764-ae40-730123de3f12)
 
<h3>1.3 Analiza testării</h3>

Procesul de testare a fost executat pe baza cerințelor aplicației.
Au fost clădite următoarele test condition-uri: 
![Screenshot (18809)](https://github.com/user-attachments/assets/45c0c12c-cc4f-4f62-adf6-aed3f952aa1c)


<h3>1.4 Proiectarea/Design-ul testării</h3>

Cazurile de testare funcționale au fost create în Zephyr Squad pe baza analizei specificațiilor. Cazurile de testare pot fi accesate aici:
[Document-TestCases](https://github.com/PokaNorbert/Primariatechirghiol.ro-Jira-Testare_Manuala-Proiect_Final/blob/main/TestCases/Document-TestCases.doc)

<h3>1.5 Implementarea testării</h3>

Următoarele elemente sunt necesare pentru a fi pregătite înainte de începerea fazei de execuție a testării:
<ul>
  <li>Mediul de testare este pregătit din toate punctele de vedere;</li>
  <li>Datele de testare sunt disponibile și exacte;</li>
  <li>Sunt grupate cele mai importante cazuri de testare;</li>
  <li>Sunt permisiuni disponibile;</li>
  <li>Smoke test-ul a fost trecut.</li>
</ul>

<h3>1.6. Execuția testării</h3>

Cazurile de testare sunt executate pe Rezumatul ciclului de testare/Cycle summary-ul creat: ”Primariatechirghiol_versiunea_1.0_limba_română”.

Au fost create defecte/bug-uri pe baza testelor eșuate. Rapoartele complete ale erorilor pot fi găsite aici:
[Document-Bugs](https://github.com/PokaNorbert/Primariatechirghiol.ro-Jira-Testare_Manuala-Proiect_Final/blob/main/Bugs/Document-Bugs.doc)

Următorul este un rezumat al defectelor/bug-urilor care au fost găsite:
![Bugs (Priority+Severity)](https://github.com/user-attachments/assets/fb73874d-6948-4595-868f-d3fae0f54dc4)

Este necesară testare completă de regresie pe zonele afectate după ce erorile sunt remediate, iar după va trebui retestată fiecare funcționalitate care a eșuat anterior.

<h3>1.7 Încheierea testării</h3>
Deoarece criteriile de ieșire au fost îndeplinite, Echipa de testare sugerează această caracteristică pentru "Go Live".

Matricea de trasabilitate a fost generată, și poate fi găsită aici:
![Screenshot (18828)](https://github.com/user-attachments/assets/37b1a9ed-a0ee-472e-8967-cf6700e3d68d)

Legătura între story-uri, teste și bug-uri/defecte este reflectată în mod corespunzător cu ajutorul Matricii de Trasabilitate: 
<ul>
  <li>Matricea de mai sus ne poate înfățișa un număr de 14 story-uri (în captura de ecran atașată sunt vizibile 10 story-uri);</li> 
  <li>Numărul ridicat de defecte/bug-uri afișat este cauzat de faptul că multe defecte sunt asociate mai multor teste, nu doar unui singur (astfel, au fost create mai multe legături nocive experienței de utilizare pe site-ul web);</li>
  <li>Story-ul denumit ”NPT-57” este legat de 5 test condition-uri: NPT-93-94-95-99-100;</li> 
  <li>Pe baza aceleași legături: ”Story-Test condition”, ”NPT-45” este legat tot de 5 test condition-uri: NPT-109-111-115-117-119, iar ”NPT-43” doar de ”NPT-121”;</li>
  <li>În total sunt 11 de test condition-uri (majoritatea acoperă mai mult de un story);</li>
  <li>Au fost identificate 15 bug-uri/defecte (acestea sunt distribuite la 11 story-uri).</li>
</ul>

Diagrama de execuție a testului a fost generată, și poate fi găsită mai jos:

![Screenshot (18812)](https://github.com/user-attachments/assets/c35f9cf2-f3a3-4e8b-b6ca-290a98fe09ca)

![Screenshot (18588) - Copy](https://github.com/user-attachments/assets/297522a8-a0b1-44c8-8103-6c2b1e24434b)

Raportul final arată că un număr de 10 teste au eșuat dintr-un total de 11.

Au fost găsite un număr de 15 defecte/bug-uri totale, dintre care niciunul nu este cu prioritate ridicată, iar 6 sunt cu prioritate medie.

<h1>Consecințe ale testării</h1>

Consecințele despre testarea efectuată reprezintă următoarele:
<ul>
  <li>Numărul total de teste create este: 11, toate fiind executate;</li>
  <li>Procentul de acoperire al testelor din domeniul de aplicare este: 100%;</li>
  <li>Pentru proiectele viitoare este nevoie de un nivel și mai ridicat al atenției umane, și de creșterea vitezei de lucru;
  <li>Majoritatea defectelor au un nivel ridicat de severitate. Toate defectele afectează interacțiunea pe care utilizatorul final o are cu site-ul web al primăriei. Așadar, există probabilitatea ca utilizatorul final să piardă timp prețios stând pe site-ul web.</li>
</ul>
