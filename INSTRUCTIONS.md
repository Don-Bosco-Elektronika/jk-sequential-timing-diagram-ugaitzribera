# 🛠️ Cronograma de Circuitos Secuenciales / Zirkuitu Sekuentzialen Kronograma / Sequential Circuit Timing Diagram

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |

---

## 📌 Ejercicio / Ariketa / Exercice

**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| 7476 | JK           | <img width="156" height="115" alt="7476 JK Sinboloa" src="https://github.com/user-attachments/assets/aa61fc75-b1ec-4e67-95ed-971d8ce45d72" />| Bi J-K flip-flop, "preset" eta "clear" funtzioekin |  

 
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| 4027 | JK             | <img width="150" height="136" alt="JK 4027 Sinboloa" src="https://github.com/user-attachments/assets/6c2c92de-6293-41bf-8790-8efb7da81075" />| Bi J-K flip-flop (CMOS teknologia), datu-biltegiratze egonkorrerako |  


---

## Tabla de la verdad

| Entrada A | Entrada B | Entrada C | Salida    | Salida |
|-----------|-----------|-----------|-----------|--------|
| 0         | 0         | 0         | ░0░       | ░0░    |
| 0         | 0         | 1         | ░1░       | ░1░    |
| 1         | 1         | 0         | ░1░       | ░1░    |
| 1         | 1         | 1         | ░0░       | ░0░    |

---

## 🔲  Simulatzeko Zirkuituak 

<img width="1270" height="483" alt="JK Proteus Ugaitz" src="https://github.com/user-attachments/assets/93222f99-c37b-4076-b768-c05b48e164ad" />


---

## 🔲  Kronogramaren Emaitza 
JK Flanco ascendente

<img width="963" height="786" alt="JK flanco ascendente ariketa" src="https://github.com/user-attachments/assets/6389c3ba-5914-4ea2-b4ac-7550b9038ee5" />


JK Flanco descendente

<img width="977" height="782" alt="JK flanco descendente ariketa" src="https://github.com/user-attachments/assets/ccc68d29-0668-4e42-bfb4-d6f7e5015804" />


---


## 🔲  Kronogramaren Kodea 
JK Flanco ascendente

{signal: [

  {name: 'clk', wave: 'P.................', period: 1},
  
  {name: 'J',   wave: '0101..0101.010.1.0'},
  
  {name: 'K',   wave: '1..0..101...01.01.'},
  
  {},
  
  {name: 'Q',   wave: '0101...0101..0.10.'},
  
  {name: '-Q',  wave: '1010...1010..1.01.'}
  
]}


JK Flanco descendente

{signal: [

  {name: 'clk',   period: 2, wave: 'N........'},
  
  {name: 'J',     wave: '0101..0101.0..1.0'},
  
  {name: 'K',     wave: '1...0..1.0..1..01'},
  
  {},
  
  {name: 'Q',     wave: '0.1...0.......1.0.'},
  
  {name: '-Q',    wave: '1.0...1.......0.1.'}
  
]}


---


## 📤  Igo 

➡️ **Instrucciones:**  

- **EU:** Igo hurrengo fitxategiak. Igotako fitxategi guztiek zure izena eduki behar dute.  
  - Sinboloaren argazki bat.  
  - Proteus fitxategia eta zirkuitu bakoitzaren irudia (captura) Proteusen.  
  - Wavedrom bakoitzaren emaitzaren kaptura (grafikoa bakarrik).  
  - **KONTUZ:** Kronogramaren kodea kodea izan behar da, ez irudi bat.



