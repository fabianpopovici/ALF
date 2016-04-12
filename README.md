<font color="red"><b>Pentru TD2 :</b></font> 
* Cerinta : Ecrivez une grammaire en PEG.js pour valider si un numero de carte de credit est vadid ou non.
* Solutia: Descrisa in urmatorii pasi : 
- verificare unitatea emitenta -> prima cifra de pe un card inseamna domeniul in care activeaza compania care l-a emis. Astfel daca cifra este: 1 si 2 inseamna companii aeriene,3 inseamna turism si entertainment,4 si 5 - banci si institutii financiare,6 inseamna merchandizing,7 - companii petroliere,8 - telecomunicatii,9 semnifica asigurarile de stat (pentru tarile unde aceste sisteme sunt bazate pe servicii de card).
- primele 6 cifre formeaza Numarul de Identificare al Emitentului: Visa - 4xxxxx,Mastercard - 51xxxx, 55xxxx,Maestro - 67xxxx. Urmatoarele 7 cifre, asadar mai putin ultima, semnifica numarul de cont al proprietarului.Ultima cifra este asa-numita "checksum", si se foloseste pentru validarea cardurilor dupa algoritmul Luhn.
-algoritmul de verificare a cardul este astfel : se impart cele 16 cifre ale numarului de card in grupuri de cate 4 cifre. Se iau prima si a treia cifra din fiecare grup si se dubleaza. Numerele dublate obtinute se aduna cu a doua si a patra cifra ramase din grupurile anterioare.Daca suma finala este divizibila cu 10, cardul de credit este valid. Daca nu, cardul de credit este invalid sau fals.
* Pentru testarea functionalitatii codului scris, am accesat platforma:  http://pegjs.org/online .
<font color="red"><b>Pentru TD3 :</b></font> 

* Cerinta : Concevez la grammaire d'un langage de programmation a l'aide de PEG.js. Le langage peut-etre imperative ou fonctionnel selon votre choix. Il faut traiter les regles pour instruction imbriquee de type if-then-else.
* Solutia este incarcata in folderul Devoir3. Sunt definite operatiile de baza intre numere, precum si caracterele(String).
* Pentru testarea functionalitatii codului scris, am accesat platforma : http://pegjs.org/online . 
