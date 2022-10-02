<html lang="en">
  <head>
    <meta charset="uft-8">
    <meta name="author" content="Masato Kubotera">
  </head>
  <body>
    <h1>EN715 Expansion Board Ver. 1.2</h1>
    <h2>About EN715 Expansion Board</h2>
    <p>
      The EN715 Expansion Board is a circuit board to expand the functions of the Carrier Board for NVIDIA Jetson manufactured by AverMedia.<br>
      <br>
      Note that this is Ver. 1.2. For other versions, please refer to the following repositories.
      <ul>
        <li><a href="https://github.com/MasatoKubotera/EN715_ExpansionBoard_ver1_0">EN715 Expansion Board Ver. 1.0</a></li>
        <li><a href="https://github.com/MasatoKubotera/EN715_ExpansionBoard_ver1_1">EN715 Expansion Board Ver. 1.1</a></li>
      </ul>
      <h2>About Ver. 1.2</h2>
      <table>
        <tr>
          <td>
            <div align="center">
              under construction<br>
              <img src="" width="320px">
            </div>
          </td>
          <td>
            <div align="center">
              under construction<br>
              <img src="" width="320px">
            </div>
          </td>
        </tr>
        <tr>
          <td>
            <div align="center">
              PCB preview image
            </div>
          </td>
          <td>
            <div align="center">
              After component mounting
            </div>
          </td>    
        </tr>
      </table>
    <h2>Repository Contents</h2>
    <p>
    <dl>
      <dt>\image</dt>
      <dd>PCB preview images and capture of design screen</dd>
      <dt>\libraries</dt>
      <dd>Libraries used in Autodesk Eagle design</dd>
      <dt>Schematic.pdf</dt>
      <dd>Circuit diagram of this product</dd>
      <dt>BOM.txt</dt>
      <dd>Parts lists output from design data</dd>
      <dt>.brd</dt>
      <dd>Board wiring design file by Autodesk Eagle</dd>
      <dt>.sch</dt>
      <dd>Schematic design file by Autodesk Eagle</dd>
      <!--
      <dt>Gerber_data.zip</dt>
      <dd>Zip folder of Gerber format files for PCB manufacturing requests.</dd>
      -->
      <dt>LICENSE</dt>
      <dd>This is a license to use this product. Please confirm before use.</dd>
      <dt>.gitignore</dt>
      <dd>File to exclude cache files from management.</dd>
    </dl>
    </p>
    <h2>Documentation</h2>
      <p>
        <h3>BOM</h3>
          <table>
            <thead>
              <tr>
                <th> Eagle Design Parts # </th>
                <th> Q'ty </th>
                <th> Mfr. Product # </th>
                <th> Supplier </th>
                <th> Description </th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td> C1, C2, C3 </td>
                <td> 3 </td>
                <td> GRM188R6YA106MA73 </td>
                <td> <a href="https://akizukidenshi.com/catalog/g/gP-13161/">Akizuki</a> </td>
                <td> Multilayer Ceramic Capacitors SMD/SMT 10uF 35V 20% 0603 </td>
              </tr>
              <tr>
                <td> C4 </td>
                <td> 1 </td>
                <td> GRM188B11H103KA01 </td>
                <td> <a href="https://akizukidenshi.com/catalog/g/gP-13387/">Akizuki</a> </td>
                <td> Multilayer Ceramic Capacitors SMD/SMT 0.01uF 50V 10% 0603 </td>
              </tr>
              <tr>
                <td> C5, C6 </td>
                <td> 2 </td>
                <td> C1608C0G1H220J080AA </td>
                <td> <a href="https://www.mouser.jp/ProductDetail/TDK/C1608C0G1H220J080AA?qs=NRhsANhppD%2FvEAPMU6eN6g%3D%3D">Mouser</a> </td>
                <td> Multilayer Ceramic Capacitors SMD/SMT 22pF 50V 5% 0603 </td>
              </tr>
              <tr>
                <td> CH1 </td>
                <td> 1 </td>
                <td> FH-2x10SG </td>
                <td> <a href="https://akizukidenshi.com/catalog/g/gC-00083/">Akizuki</a> </td>
                <td> 2.54mm Pin Socket, 2 Row, 20 Pin </td>
              </tr>
              <tr>
                <td> CR1 </td>
                <td> 1 </td>
                <td> FA-238V 12.0000MB-K3 </td>
                <td> <a href="https://akizukidenshi.com/catalog/g/gP-05225/">Akizuki</a> </td>
                <td> Crystals 12.0000MHz 50ppm 10pF -40C +85C </td>
              </tr>
              <tr>
                <td> D1, D2, D3, D4, D5, D6, D7, D8, D9, D10 </td>
                <td> 10 </td>
                <td> CG0603MLC-05E </td>
                <td> <a href="https://www.mouser.jp/ProductDetail/Bourns/CG0603MLC-05E?qs=lDok7oSghXVLNKMK69q%252BFQ%3D%3D">Mouser</a> </td>
                <td> ESD Protectors 5V 0603 </td>
              </tr>
              <tr>
                <td> F1 </td>
                <td> 1 </td>
                <td> MF-MSMF050-2 </td>
                <td> <a href="https://www.mouser.jp/ProductDetail/Bourns/MF-MSMF050-2?qs=t3shhpq1i1DZ7OBD5kLNoA%3D%3D">Mouser</a> </td>
                <td> PTC Resettable Fuses 15V .5A-HD 100A MAX </td>
              </tr>
              <tr>
                <td> FL1, FL2, FL3, FL4, FL5 </td>
                <td> 5 </td>
                <td> BLM18SD220SN1D </td>
                <td> <a href="https://www.mouser.jp/ProductDetail/Murata-Electronics/BLM18SD220SN1D?qs=glnLrWX4TPq%2Fm8%2FdPQltLg%3D%3D">Mouser</a> </td>
                <td> Ferrite Beads 22 OHM 0603 </td>
              </tr>
              <tr>
                <td> IC1 </td>
                <td> 1 </td>
                <td> FE1.1S </td>
                <td> <a href="https://www.aitendo.com/product/16185">aitendo</a> </td>
                <td> USB Interface IC USB 2.0 Hi-Speed 4 Port Hub Controller </td>
              </tr>
              <tr>
                <td> LED1 </td>
                <td> 1 </td>
                <td> 150060VS86000 </td>
                <td> <a href="https://www.mouser.jp/ProductDetail/Wurth-Elektronik/150060VS86000?qs=GedFDFLaBXGW9qOjzZ1Hmw%3D%3D">Mouser</a> </td>
                <td> Standard LEDs - SMD Green 2V 20mA 573nm 0603 </td>
              </tr>
              <tr>
                <td> LED2, LED3, LED4, LED5, LED6 </td>
                <td> 5 </td>
                <td> 150060YS75000 </td>
                <td> <a href="https://www.mouser.jp/ProductDetail/Wurth-Elektronik/150060YS75000?qs=LlUlMxKIyB0nKmwefHgtZw%3D%3D">Mouser</a> </td>
                <td> Standard LEDs - SMD Yellow 2V 20mA 590nm 0603 </td>
              </tr>
              <tr>
                <td> M1 </td>
                <td> 1 </td>
                <td> SEN-15335 </td>
                <td> <a href="https://www.mouser.jp/ProductDetail/SparkFun/SEN-15335?qs=uwxL4vQweFMcls1MYZT00A%3D%3D">Mouser</a> </td>
                <td> 9-Axis MotionTracking Device Module </td>
              </tr>
              <tr>
                <td> M1 </td>
                <td> 1 </td>
                <td> 6604S-40 </td>
                <td> <a href="https://akizukidenshi.com/catalog/g/gP-01591/">Akizuki</a> </td>
                <td> 2.54mm Pin Socket Strip, Single Row </td>
              </tr>
              <tr>
                <td> M1 </td>
                <td> 1 </td>
                <td> PHA-1x40SG </td>
                <td> <a href="https://akizukidenshi.com/catalog/g/gC-06631/">Akizuki</a> </td>
                <td> 2.54mm Pin Header Strip, Straight, Single Row </td>
              </tr>
              <tr>
                <td> R1, R3, R4, R5 </td>
                <td> 4 </td>
                <td> RC0603FR-101KL </td>
                <td> <a href="https://www.mouser.jp/ProductDetail/YAGEO/RC0603FR-101KL?qs=EiqXWrxQq63MM0wzm69ZKg%3D%3D">Mouser</a> </td>
                <td> Thick Film Resistors - SMD 1 kOhms 100-200mW 1% 0603 </td>
              </tr>
              <tr>
                <td> R2 </td>
                <td> 1 </td>
                <td> RC0603FR-102K7L </td>
                <td> <a href="https://www.mouser.jp/ProductDetail/YAGEO/RC0603FR-102K7L?qs=Iqe6t0HYRD6Xaw3IgOqXnw%3D%3D">Mouser</a> </td>
                <td> Thick Film Resistors - SMD 2.7 kOhms 100-200 mW 1% 0603 </td>
              </tr>
              <tr>
                <td> USB1 </td>
                <td> 1 </td>
                <td> MUSB-5B-NE-S175 </td>
                <td> <a href="https://akizukidenshi.com/catalog/g/gC-05843/">Akizuki</a> </td>
                <td> Mini USB Connector 5P B type, Female, SMT type, without standoff </td>
              </tr>
              <tr>
                <td> USB2, USB3, USB4, USB5 </td>
                <td> 4 </td>
                <td> USB1046-GF-0190-L-B-A </td>
                <td> <a href="https://www.mouser.jp/ProductDetail/640-USB1046GF0190LBA">Mouser</a> </td>
                <td> USB Connectors USB2.0 A, Top Mount, SMT </td>
              </tr>
            </tbody>
          </table>
        <!--
        <h3>PCB Fabrication</h3>
          PCB(Printed Circuit Board) manufacturing was outsourced to <a href="https://www.elecrow.com/pcb-manufacturing.html">Elecrow</a>.<br>
          The custom specifications are as follows.
          <ul>
            <li>Layer : 2 layers</li>
            <li>Dimensions : 87 x 50</li>
            <li>PCB Qty : 10</li>
            <li>Different PCB Design : 1eg</li>
            <li>PCB Thickness : 1.6</li>
            <li>PCB Color : Black</li>
            <li>Surface Finish : HASL Lead Free</li>
            <li>Castellated Hole : No</li>
            <li>Copper Weight : 1oz</li>
            <li>PCB Stencil : Stencil 15cm X 15cm no frame</li>
          </ul>
          The data used to order fabrication are as follows.
          <ul>
            <li>Eagle design rule : <a href="https://www.elecrow.com/download/Elecrow_PCB_eagle_rule.zip">Elecrow Eagle Design Rule</a></li>
            <li>Eagle CAM file : <a href="https://www.elecrow.com/download/Elecrow_Gerber_Generater_DrillAlign.zip">Elecrow CAM file</a></li>
            <li>Gerber format data : <a href="/Gerber_data.zip">Gerber_data.zip</a></li>
          </ul>
      </p>
      -->
    <h2>Contact</h2>
    <p>
    If you have any questions, please contact MasatoKubotera, the product's designer, by E-mail.<br>
    E-mail : <a href="mailto:masatokubotera06@yahoo.co.jp">masatokubotera06@yahoo.co.jp</a>
    </p>
    <h2>License Information</h2>
    <p>
      This product is open source.<br>
      Please review the <a href="/LICENSE">LICENSE file</a> for license information.<br>
      <br>
      <strong>EN715 Expansion Board Ver. 1.2</strong> by Masato Kubotera is licensed under a <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
    </p>
  </body>
</html>
