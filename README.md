# Povprečne mesečne plače po občinah

## Opis problema

Izbran problem (oziroma zbirka podatkov) je Povprečne mesečne plače po občinah, Slovenija, letno.

Problem zajema povprečne bruto in neto plače po občinah v Sloveniji, z dodatnimi podatki kot so opravljene (oz. plačane) nadure, število oseb, ki so opravljale nadure na mesec, število oseb, ki so prejele zaostala izplačila itd.

Vse vrednosti so povprečne mesečne vrednosti, ki so razdeljena na leta (npr. povp. neto plača na mesec v letu 2015 itd.)

Ti podatki podajo več zanimivih vprašanj, kot npr.:
  * V katerij regijah Slovenije so plače višje/nižje?
  * Kako izgleda rast/upad plač skozi leta (posledice recesije?)?
  * Kje je opravljenih največ nadur, in kje so te najbolje plačane?
  * Kakšne so vrednosti, če upoštevano/primerjmo inflacijo?
  
Cilj je seveda analiza, pregled in vizualizacija teh podatkov, ter njihova razdelitev po regijah. Zanima nas tudi razporeditev plač po Sloveniji.

## Podatki

V podatkovni datoteki so podane sledeče vrednosti:
 * Povprečna mesečna bruto plača
 * Povprečna mesečna neto plača
 * Indeks povprečne mesečne bruto plače
 * Indeks povprečne mesečne neto plače
 * Povprečna plača za plačano naduro
 * Povprečna mesečna bruto plača za plačano uro
 * Povprečna mesečna neto plača za plačano uro
 * Indeks povprečne mesečne bruto plače za plačano uro
 * Indeks povprečne mesečne neto plače za plačano uro
 * Zaposlene osebe, ki so prejele zaostala izplačila
 * Zaposlene osebe z izplačanimi nadurami
 
Vrednosti so za leta od 2005 do 2019, in so povprečja celotnega leta za posamezne občine v Sloveniji (katerih je 211).

Iz podatkov sva odstranila vnose za občine Ankaran in Mirna, saj so tem občinam manjkali podatki za vrsto let (tako je skupaj 209 občin). Odstranila sva tudi leto 2005 za indeks povprečne mesečne plače za plačano uro, saj je to leto bilo popolnoma prazno.

Za potrebe analize sva uporabljala samo neto vrednosti (namesto bruto), saj ponujajo boljšo predstavitev dejanskega denarnega prihodka za posamezno občino.

## Predstavitev podatkov

### Največja povprečna neto plača

Pri vseh letih je največja plača v občini **Cerklje na Gorenjskem**. Sledeče vrednosti so največje 3 neto plače, v vsakem stolpcu urejene po barvi kjer **najtemnejša == največja plača**.

<html>
<style  type="text/css" >
    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col0 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col1 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col2 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col3 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col4 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col5 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col6 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col7 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col8 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col9 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col10 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col11 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col12 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col13 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col14 {
            background-color:  #FF6200;
            : ;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col0 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col0 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col1 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col2 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col3 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col4 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col5 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col6 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col7 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col8 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col9 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col10 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col11 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col12 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col13 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col14 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col1 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col2 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col3 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col5 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col6 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col7 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col4 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col8 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col9 {
            : ;
            background-color:  #FD9346;
            : ;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col10 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col11 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col12 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col13 {
            : ;
            : ;
            background-color:  #FDB777;
        }    #T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col14 {
            : ;
            background-color:  #FD9346;
            : ;
        }</style><table id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >2005</th>        <th class="col_heading level0 col1" >2006</th>        <th class="col_heading level0 col2" >2007</th>        <th class="col_heading level0 col3" >2008</th>        <th class="col_heading level0 col4" >2009</th>        <th class="col_heading level0 col5" >2010</th>        <th class="col_heading level0 col6" >2011</th>        <th class="col_heading level0 col7" >2012</th>        <th class="col_heading level0 col8" >2013</th>        <th class="col_heading level0 col9" >2014</th>        <th class="col_heading level0 col10" >2015</th>        <th class="col_heading level0 col11" >2016</th>        <th class="col_heading level0 col12" >2017</th>        <th class="col_heading level0 col13" >2018</th>        <th class="col_heading level0 col14" >2019</th>    </tr>    <tr>        <th class="index_name level0" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689level0_row0" class="row_heading level0 row0" >Cerklje na Gorenjskem</th>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col0" class="data row0 col0" >994.07</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col1" class="data row0 col1" >1,028.63</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col2" class="data row0 col2" >1,065.88</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col3" class="data row0 col3" >1,179.98</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col4" class="data row0 col4" >1,147.61</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col5" class="data row0 col5" >1,173.70</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col6" class="data row0 col6" >1,182.71</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col7" class="data row0 col7" >1,187.71</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col8" class="data row0 col8" >1,378.65</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col9" class="data row0 col9" >1,393.08</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col10" class="data row0 col10" >1,431.88</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col11" class="data row0 col11" >1,404.53</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col12" class="data row0 col12" >1,438.70</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col13" class="data row0 col13" >1,445.17</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row0_col14" class="data row0 col14" >1,433.90</td>
            </tr>
            <tr>
                        <th id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689level0_row1" class="row_heading level0 row1" >Kobilje</th>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col0" class="data row1 col0" >857.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col1" class="data row1 col1" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col2" class="data row1 col2" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col3" class="data row1 col3" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col4" class="data row1 col4" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col5" class="data row1 col5" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col6" class="data row1 col6" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col7" class="data row1 col7" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col8" class="data row1 col8" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col9" class="data row1 col9" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col10" class="data row1 col10" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col11" class="data row1 col11" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col12" class="data row1 col12" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col13" class="data row1 col13" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row1_col14" class="data row1 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689level0_row2" class="row_heading level0 row2" >Ljubljana</th>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col0" class="data row2 col0" >848.09</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col1" class="data row2 col1" >889.75</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col2" class="data row2 col2" >963.60</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col3" class="data row2 col3" >1,042.35</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col4" class="data row2 col4" >1,081.27</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col5" class="data row2 col5" >1,106.95</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col6" class="data row2 col6" >1,125.64</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col7" class="data row2 col7" >1,124.97</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col8" class="data row2 col8" >1,125.61</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col9" class="data row2 col9" >1,130.74</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col10" class="data row2 col10" >1,140.33</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col11" class="data row2 col11" >1,159.83</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col12" class="data row2 col12" >1,197.56</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col13" class="data row2 col13" >1,231.47</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row2_col14" class="data row2 col14" >1,281.66</td>
            </tr>
            <tr>
                        <th id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689level0_row3" class="row_heading level0 row3" >Sveta Ana</th>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col0" class="data row3 col0" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col1" class="data row3 col1" >886.28</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col2" class="data row3 col2" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col3" class="data row3 col3" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col4" class="data row3 col4" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col5" class="data row3 col5" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col6" class="data row3 col6" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col7" class="data row3 col7" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col8" class="data row3 col8" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col9" class="data row3 col9" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col10" class="data row3 col10" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col11" class="data row3 col11" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col12" class="data row3 col12" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col13" class="data row3 col13" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row3_col14" class="data row3 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689level0_row4" class="row_heading level0 row4" >Dol pri Ljubljani</th>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col0" class="data row4 col0" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col1" class="data row4 col1" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col2" class="data row4 col2" >955.73</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col3" class="data row4 col3" >1,066.81</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col4" class="data row4 col4" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col5" class="data row4 col5" >1,066.37</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col6" class="data row4 col6" >1,119.90</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col7" class="data row4 col7" >1,120.90</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col8" class="data row4 col8" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col9" class="data row4 col9" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col10" class="data row4 col10" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col11" class="data row4 col11" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col12" class="data row4 col12" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col13" class="data row4 col13" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row4_col14" class="data row4 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689level0_row5" class="row_heading level0 row5" >Sveti Tomaž</th>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col0" class="data row5 col0" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col1" class="data row5 col1" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col2" class="data row5 col2" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col3" class="data row5 col3" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col4" class="data row5 col4" >1,052.42</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col5" class="data row5 col5" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col6" class="data row5 col6" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col7" class="data row5 col7" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col8" class="data row5 col8" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col9" class="data row5 col9" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col10" class="data row5 col10" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col11" class="data row5 col11" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col12" class="data row5 col12" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col13" class="data row5 col13" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row5_col14" class="data row5 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689level0_row6" class="row_heading level0 row6" >Novo mesto</th>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col0" class="data row6 col0" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col1" class="data row6 col1" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col2" class="data row6 col2" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col3" class="data row6 col3" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col4" class="data row6 col4" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col5" class="data row6 col5" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col6" class="data row6 col6" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col7" class="data row6 col7" >0.00</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col8" class="data row6 col8" >1,116.34</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col9" class="data row6 col9" >1,145.87</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col10" class="data row6 col10" >1,138.56</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col11" class="data row6 col11" >1,149.06</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col12" class="data row6 col12" >1,173.36</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col13" class="data row6 col13" >1,217.78</td>
                        <td id="T_d31a4226_7443_11ea_b60f_c8d3ffd17689row6_col14" class="data row6 col14" >1,286.19</td>
            </tr>
    </tbody></table>
</html>

