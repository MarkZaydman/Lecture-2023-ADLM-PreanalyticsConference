---

marp: true
theme: default
color: #000
backgroundColor: #fff
enableHtml: true	
paginate: true
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
  .columns-left {
    background: white;
  }
  .columns-right {
    background: white;
  }


---


# Reducing Speimen Hemolysis and Blood Culture Contamination in the Emergency Department Through Automated Collector

<br>

<div class='columns'>
<div class='columns-left'>


### Mark A Zaydman, MD, PhD
Assistant Professor 
Department of Pathology and Immunology
Washington University School of Medicine

</div>
<div class='columns-right' sytle='align:center'>

<img src='./assets/School_of_Medicine_2linecnt_pos_RGB_1000-01.png' height="350" align='right'>

</div>
</div>

---


<h1>
  Disclosures
</h1>
<h5>
  Research Support
</h5>
<p>
  bioMerieux 
</p>
<h5>
  Speaking Honoraria
</h5>
<p>
  Sebia - "A Modern Approach to Screening for MGs using Digital Workflows"<br>
  Siemens - "FLC Testing in Multiple Myeloma and Kidney Disease"<br>
  API - 2023 Annual Summit (Pittsburgh, PA)<br>
  ADLM - 2023 Annual Scientific Meeting (Anaheim, CA)
</p>
<h5>
  Patents
</h5>
<p>
  US20210311046 - Method of Reducing Interference in Immunoassays
  WO2022198218A1 - Spectral Correlation Analysis of Layered Evolutionary Signals
</p>

---

<h1>Errors Occuring During Specimen Collection</h1>

<br>

<img src='./assets/Preanalytical_Errors.png' style='margin-left:30px'>

---


<h1><i>In vitro</i> Hemolysis Occurs During or After Collection</h1>
<br>
<div class='columns'>
  <div class='columns-left'>
    <p style='padding-left:10px'>
      <ins><i>In vitro</i> hemolysis</ins> <br><br>
      Non-biological rupturing of blood cells leading to the release of intracellular contents into the fluid fraction of the specimen (ex. Potassium, Hemoglobin)
    </p>
  </div>
  <div class='columns-right'>
    <img src='./assets/HemolysisDuringCollection.png' style='margin-left:10px' >
  </div>
</div>
<br>
<p style='font-size:16px;text-align:right'>
Lippi, Giuseppe, Gianfranco Cervellin, and Camilla Mattiuzzi. “Critical Review and Meta-Analysis of Spurious Hemolysis in Blood Samples Collected from Intravenous Catheters.” Biochemia Medica, 2013, 193–200. https://doi.org/10.11613/BM.2013.022.
</p>

---

<h2><i>In vitro</i> Hemolysis Interfers with Laboratories in Complex Ways</h2>
<br>
<div class='columns'>
  <div class='columns-left'>
    <p style='padding-left:10px'>
      <ins>Hemoytic inteference mechanisms</ins><br>
      &nbsp;- Elevation of intracellular analytes<br>
      &nbsp;- Dilution of extracellular analytes<br>
      &nbsp;- Optical interferance<br>
      &nbsp;- Enzymatic interferance<br>
    </p>
  </div>
  <div class='columns-right'>
    <img src='./assets/Hemolysis.png' style='margin-left:10px'>
  </div>
</div>
<br>
<p style='font-size:16px;text-align:right'>
  Lippi, Giuseppe, Norbert Blanckaert, Pierangelo Bonini, Sol Green, Steve Kitchen, Vladimir Palicka, Anne J. Vassault, and Mario Plebani. “Haemolysis: An Overview of the Leading Cause of Unsuitable Specimens in Clinical Laboratories.” Clinical Chemistry and Laboratory Medicine 46, no. 6 (January 1, 2008). https://doi.org/10.1515/CCLM.2008.170.
</p>


---

<h2><i>In vitro</i> Hemolysis is the Most Common Cause of Sample Rejection</h2>
<br>
<div class='columns'>
  <div class='columns-left'>
    <p style='padding-left:10px'>
      Inaccurate results can harm patients
    </p>
    <p style='padding-left:10px'>
      Laboratories monitor for free Hgb<br>
      &nbsp;- Visual inspection<br>
      &nbsp;- Spectrophotometric detection<br>
    </p>
    <p style='padding-left:10px'>
      Hemolyzed specimens may be rejected<br>
      &nbsp;- the most frequent cause of rejection
    </p>
  </div>
  <div class='columns-right'>
    <img src='./assets/HemolysisRejection.png' style='margin-left:10px' width=700>
  </div>
</div>
<br>
<p style='font-size:16px;text-align:right'>
  Jones, B. A., R. R. Calam, and P. J. Howanitz. “Chemistry Specimen Acceptability: A College of American Pathologists Q-Probes Study of 453 Laboratories.” Archives of Pathology & Laboratory Medicine 121, no. 1 (January 1997): 19–26.
</p>

---

<h2>Specimen Rejection Degrades Care and Increases Costs</h2>
<div class='columns'>
  <div class='columns-left'>
    <p style='padding-left:10px'>
      <strong><ins>Degraded care</ins></strong><br>
      &nbsp;- Delayed/missed diagnosis<br>
      &nbsp;- Repeat phlebotomy<br>
    </p>
    <p style='padding-left:10px'>
      <strong><ins>Increased costs</ins></strong><br>
      &nbsp;- Prolonged length of stay<br>
      &nbsp;- Consumables<br>
      &nbsp;- Nurse/phlebotomists time<br>
      &nbsp;- Laboratory resources<br>
      &nbsp;- Downstream harms of medical errors*<br>
      &emsp;*Difficult to account for
    </p>    
  </div>
  <div class='columns-right'>
    <table style='padding-top:10px;padding-bottom:10px;text-align:center'>    
      <tr>
        <th>Setting</th>
        <th>Costs</th>
        <th>Reference</th>
      </tr>
      <tr>
        <td>Emergency</td>
        <td>$600.00</td>
        <td style='font-size:16px'>Phelan, Michael P., et. al., JALM 6(6):2021, <br>Pgs 1607–1610</td>
      </tr>                              
      <tr>
        <td>Inpatient</td>
        <td>$357.15</td>
        <td style='font-size:16px'>Green, Sol F. Clin Biochem 46(13-14):2013,<br>Pgs 1175–79</td>
      </tr>
      <tr>
        <td>Critical care</td>
        <td>$162.18</td>
        <td style='font-size:16px'>Green, Sol F. Clin Biochem 46(13-14):2013,<br>Pgs 1175–79</td>
      </tr>
      <tr>
        <td>Outpatient</td>
        <td>$337.05</td>
        <td style='font-size:16px'>Green, Sol F. Clin Biochem 46(13-14):2013,<br>Pgs 1175–79</td>
      </tr>
    </table>
  </div>
</div>
<br>
<p style='font-size:16px;text-align:right'>
  Doern, Gary V., Karen C. Carroll, Daniel J. Diekema, Kevin W. Garey, Mark E. Rupp, Melvin P. Weinstein, and Daniel J. Sexton. “Practical Guidance for Clinical Microbiology Laboratories: A Comprehensive Update on the Problem of Blood Culture Contamination and a Discussion of Methods for Addressing the Problem.” Clinical Microbiology Reviews 33, no. 1 (December 18, 2019): e00009-19. https://doi.org/10.1128/CMR.00009-19.
</p>


---

<h1>
  Hemolysis is a Common Preanalytical Error
</h1>
<div class='columns'>
  <div class='columns-left'>
  </div>
  <div class='columns-right'>
  </div>  
</div>

---

<h1>
  Training and Feedback Reduce Hemolysis Rates
</h1>
<div class='columns'>
  <div class='columns-left'>
  </div>
  <div class='columns-right'>
  </div>  
</div>

---


<h1>Blood Culture Contamination</h1>
<br>
<div class='columns'>
  <div class='columns-left'>
    <p style='padding-left:10px'>
      <ins>Blood culture contamination</ins>
    </p>
    <p style='padding-left:10px'>
      The introduction of non-pathogenic bacteria from the patients skin or environment into a blood culture speimen during collection giving the false impression that the patient has a blood stream infection 
    </p>
  </div>
  <div class='columns-right'>
    <img src='./assets/BloodCultureContamination.png' style='margin-left:10px' >
  </div>
</div>
<br>
<p style='font-size:16px;text-align:right'>
  Doern, Gary V., Karen C. Carroll, Daniel J. Diekema, Kevin W. Garey, Mark E. Rupp, Melvin P. Weinstein, and Daniel J. Sexton. “Practical Guidance for Clinical Microbiology Laboratories: A Comprehensive Update on the Problem of Blood Culture Contamination and a Discussion of Methods for Addressing the Problem.” Clinical Microbiology Reviews 33, no. 1 (December 18, 2019): e00009-19. https://doi.org/10.1128/CMR.00009-19.
</p>

---



<h1>Blood Culture Contamination Causes Broad Harms</h1>

<div class='columns'>
  <div class='columns-left'>
    <p style='padding-left:10px'>
      <ins>Patient</ins> <br>
      - 3 additional days of IV antibiotics<br>
      - 1-5 additional days of hospitalization<br>
      - $9,000 additional hospitalization costs
    </p>
    <p style='padding-left:10px'>
      <ins>Microbiology lab</ins> <br>
      - Technician time<br>
      - Reagents
    </p>    
    <p style='padding-left:10px'>
      <ins>Hospital</ins> <br>
      - Costs  of prolonged hospitalization<br>
      - Quality penalties (CLABSI)
    </p>        
    <p style='padding-left:10px'>
      <ins>Public</ins> <br>
      - Increase prevalence of MDRO
    </p>        
  </div>
  <div class='columns-right'>
    <img src='./assets/HarmsofBCC.png' style='margin-left:120px' width=400>
    <br><br>
    <p style='font-size:16px;text-align:right'>
      Bates, David W. JAMA 265, no. 3 (January 16, 1991): 365. <br>
      Gander, RM et. al. JCM 47, no. 4 (April 2009): 1021–24.<br>
      Doern, GV et al. CMR 33, no. 1 (December 18, 2019): e00009-19.<br>
    </p>
  </div>
</div>

---

<h1>
  Blood Culture Contamination is Common
</h1>
<div class='columns'>
  <div class='columns-left'>
  </div>
  <div class='columns-right'>
  </div>  
</div>

---

<h1>
  Training and Feedback Reduce Contamination Rates
</h1>
<div class='columns'>
  <div class='columns-left'>
  </div>
  <div class='columns-right'>
  </div>  
</div>

---

<h2>
 Barriers to Implementing Collector Feedback and Training 
</h2>
<br>
<div>
  <img src='./assets/barriers.png' width=2000>
</div>

---

<h2>
  Our Hypothesis
</h2>
<p>
  We hypothesized that digital technologies        can remove the barriers to mounting an effective education and feedback campaign to reduce specimen collection error rates
</p>
<center>
<div style='padding-top:10px'>
  <img src='./assets/informaticsandtechonlogy.png' height=450>
</div>
</center>


---

<h1>
  Our goal
</h1>
<p>
  To develop an end-to-end automated solution to provide scalable and sustainable collector feedback and performance-based training to reduce specimen collection errors 
</p>
<div style='margin:10px'>
  <img src='./assets/aces_architecture.png' style='padding-left:400;padding-top:10;' width=650>
</div>

---

<div style='border-bottom:solid;border-width:thick;border-color:gray'>
  <h2>
    Outline for this Talk 
  </h2>
</div>
<div style='padding-left:40px;padding-top:0px'>
  <h3>
    Part 1
  </h3>
  <div style='border:solid;margin-left:0px;margin-right:40px;border-radius:20px;text-align:center;padding-top:10px;margin-left:10px'>
    <p style='padding-left:20px;'>
      Estimating the institution-level costs of <br>blood specimen hemolysis and blood culture contamination
    </p>
  </div>
  <h3>
    Part 2
  </h3>
  <div style='border:solid;margin-left:0px;margin-right:40px;border-radius:20px;text-align:center;padding-top:10px;margin-left:10px'>
    <p style='padding-left:20px;'>
      Automating the dectection of underperforming specimen collectors
    </p>
  </div>  
  <h3>
    Part 3
  </h3>
  <div style='border:solid;margin-left:0px;margin-right:40px;border-radius:20px;text-align:center;padding-top:10px;margin-left:10px;margin-bottom:10px'>  
    <p style='padding-left:20px'>
      Automating the delivery of personalized collector feedback and training
    </p>
  </div>
</div>
<br>
<br>


---
<h1>
  Part 1
</h3>
<div style='border:solid;margin-left:0px;margin-right:40px;border-radius:20px;text-align:center;padding-top:10px;margin-left:10px'>
  <p style='padding-left:20px;'>
  Estimating the institution-level costs of <br>blood specimen hemolysis and blood culture contamination
    </p>
</div>


---


<div class="columns">
  <div class="columns-left">
    <h1>
      Study Context
    </h1>
    <h5>
      Barnes-Jewish Hospital (BJH)
    </h5>
    <p>
      &bull; St. Louis, Missouri, USA<br>
      &bull; 1266 adult beds<br>
      &bull; Tertiary academic care center<br>
      &emsp;- Washington University<br>&emsp;&nbsp;&nbsp;&nbsp;School of Medicine<br>
    </p>
</div>
  <div class="columns-right">
    <img align="left" src="./assets/bjc.jpeg" hspace=40 vspace=5 width="450" alt="pic"/> 
    <img align="left" src="./assets/bjh_logo.png" hspace=40 vspace=0 width="450" alt="pic"/> 
  </div>
</div>

---

<h2>
  Methods (estimating hemolysis costs)
</h2>
<div class="columns">
  <div class="columns-left">
    <!-- <h3>
      <ins>Hemolysis costs</ins>
    </h3> -->
    <strong>Retrospective:</strong> 1/1/2022 to 1/1/2023<br>
    <strong>Single-institution:</strong> Barnes-Jewish Hospital<br>
    <strong>Study design:</strong> Observational<br>
    <strong>Data source:</strong> LIS (Cerner Millenium, Oracle)
    <strong>Inclusion criteria:</strong> <br>
    &emsp;&bull; Specimen drawn in study period<br>
    &emsp;&bull; Hemolysis index (HI) measured<br>
    <strong>Cost model:</strong> <br>
    &emsp;&bull; Redrawn if HI > threshold for 1+ analyte<br>
    &emsp;&bull; Fixed, context dependent redraw costs<br>
  </div>
  <div class="columns-left" style='margin-left:20px'>
    <table style='padding-top:0px;padding-bottom:10px;text-align:center'>    
      <tr>
        <th>Setting</th>
        <th>Costs</th>
        <th>Reference</th>
      </tr>
      <tr>
        <td>Emergency</td>
        <td>$600.00</td>
        <td style='font-size:16px'>Phelan, Michael P., et. al., JALM 6(6):2021, <br>Pgs 1607–1610</td>
      </tr>                              
      <tr>
        <td>Inpatient</td>
        <td>$357.15</td>
        <td style='font-size:16px'>Green, Sol F. Clin Biochem 46(13-14):2013,<br>Pgs 1175–79</td>
      </tr>
      <tr>
        <td>Critical care</td>
        <td>$162.18</td>
        <td style='font-size:16px'>Green, Sol F. Clin Biochem 46(13-14):2013,<br>Pgs 1175–79</td>
      </tr>
      <tr>
        <td>Outpatient</td>
        <td>$337.05</td>
        <td style='font-size:16px'>Green, Sol F. Clin Biochem 46(13-14):2013,<br>Pgs 1175–79</td>
      </tr>
    </table>
  </div>
</div>

---


<div class="columns">
  <div class="columns-left">
    <h1>
      Hemolysis Indices
    </h1>
    Automated detection and quantitation<br>
    Based on spectrophotemetric measurement<br><br>
    <ins>BJH</ins><br>
    Measured on Roche Cobas c702<br>
    Plasma samples<br>
  </div>
  <div class="columns-right">
    <center>
      <img src='./assets/hgb_wavelength.png' style='margin-left:40px'>
      <img src='./assets/hgb_hi_calibration.png'>
    </center>
  </div>
</div>
<p style='font-size:18px;text-align:right'>
  Ishiguro, Akiyo, Mitsuaki Nishioka, Akihiro Morishige, Reo Kawano, Toshihiko Kobayashi, Aki Fujinaga, Fumiya Takagi, et al. “What Is the Best Wavelength for the Measurement of Hemolysis Index?” Clinica Chimica Acta 510 (November 2020): 15–20. https://doi.org/10.1016/j.cca.2020.06.046.
</p>



---

<h3>
  Annual Institutional Hemolysis Redraw Costs are Nearly $4,000,000
</h3>
<div class="columns" style='margin-top:20px'>
  <div class="columns-left">
    <ins>
      Assumptions<br>
    </ins>
    &bull; Results supressed for HI > threshold<br>
    &bull; All specimen with supressed results <br>&emsp;incur redraw costs
  </div>
  <div class="columns-right">
    <table style='margin-top:0px;margin-left:50px;text-align:right'>
      <tr>
        <td>
          # specimens
        </td>
        <td>
          620,756
        </td>        
      </tr>
      <tr>
        <td>
          # collectors
        </td>
        <td>
          4994
        </td>        
      </tr>
      <tr>
        <td>
          HI > 50
        </td>
        <td>
          12.1%
        </td>        
      </tr>    
      <tr>
        <td>
          HI > 100
        </td>
        <td>
          5.0%
        </td>        
      </tr>
      <tr>
        <td>
          HI > 250
        </td>
        <td>
          1.4%
        </td>        
      </tr>   
      <tr>
        <td>
          Rejection rate
        </td>
        <td>
          1.6%
        </td>        
      </tr>   
      <tr>
        <td>
          Total costs
        </td>
        <td>
          $3,910,530.54
        </td>        
      </tr>                          
    </table>
  </div>
</div>


---


<!-- <div class="columns"> -->
  <!-- <div class="columns-left"> -->
<h3>
  Emergency and Inpatient Settings Account Majority of Redraw Costs
</h3>
<div class='columns'>
  <div class='columns-left' style='margin-top:50px'>
    <!-- &bull; Each account for ~40% of total costs<br> -->
    &bull; Inpatient costs are driven by volume<br>
    &bull; ED costs driven by error rates and <br>&emsp; higher redraw costs <br>
  </div>
  <div class='columns-right'>
    <img src='./assets/encounter_type_summary.png' width=550>
  </div>
</div>

---

<h2>
  Most Hemolysis Costs Arise from a Small Number of Collectors
</h2>
<div class="columns" style='margin-top:20px'>
  <div class="columns-left">
    <center>
    <ins>
      Pareto Principle<br>
    </ins>
    <div style='text-align:center;border:solid;border-radius:10px;margin:20px;padding:10px'>
      ~20% of the collectors <br>are responsible for <br>~80% of the total hemolysis costs
    </div>
    </center>
  </div>
  <div class="columns-right">
    <center>
      <img src='./assets/pareto_all.png' width=400>
    </center>
  </div>
</div>

---

<h2>
  Pareto Principle Appears Across Patient Encounter Types
</h2>
<div class="columns" style='margin-top:20px'>
  <div class="columns-left">
    Hemolysis costs across different patient care setting arise from a subset of collectors
  </div>
  <div class="columns-right">
    <center>
      <img src='./assets/pareto_byType.png' width=500>
    </center>
  </div>
</div>

---

<div style='border:solid;text-align:center;border-radius:10px;padding:10px'>
  How to identify the subset of collectors that are responsible for the majority of costs?
</div>

---

  <h3>
    Part 2
  </h3>
  <div style='border:solid;margin-left:0px;margin-right:40px;border-radius:20px;text-align:center;padding-top:10px;margin-left:10px'>
    <p style='padding-left:20px;'>
      Automating the dectection of underperforming specimen collectors
    </p>
  </div>  
  
---

# Identifying high value targets for collector retraining

---

# Delivering automated feedback and training to reduce specimen collection errors


---

<h2>
  Methods (estimating blood culture contamination costs)
</h2>
<div class="columns">
  <div class="columns-left">
    <h3>
      <ins>Blood culture contamination costs</ins>
    </h3>
    <strong>Retrospective:</strong> xx/xx/xxxx to yy/yy/yyyy<br>
    <strong>Single-institution:</strong> Barnes-Jewish Hospital<br>
    <strong>Study design:</strong> Observational<br>
    <strong>Data source:</strong> LIS (Cerner Millenium, Oracle)
    <strong>Inclusion criteria:</strong> <br>
    &emsp;&bull; Specimen drawn in study period<br>
    <strong>Contamination logic:<br></strong>
    &emsp;&bull; Grew likely commensual<br>
    &emsp;&bull; No repeat positive +/- 3 days<br>
    <strong>Cost model:</strong> <br>
    &emsp;&bull; Context dependent costs<br>
  </div>
  <div class="columns-left" style='margin:20px'>
    BCC costs cartoon goes here
  </div>
</div>

