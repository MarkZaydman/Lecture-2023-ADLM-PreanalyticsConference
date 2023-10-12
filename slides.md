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


# Preventing Specimen Hemolysis and Blood Culture Contamination with Automated Collector Evaluations

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

<h1>
  Hemolysis and Blood Culture Contamination
</h1>

> Common and costly errors occuring during specimen collection

<div style='margin-top:40px'>
  <img src='./assets/Preanalytical_Errors.png' style='margin-left:30px'>
</div>

---


<!-- <h1><i>In vitro</i> Hemolysis Occurs During or After Collection</h1> -->
<!-- <br> -->
<div class='columns'>
  <div class='columns-left'>
    <p style='padding-left:10px'>
      <h3>
        <ins><i>In vitro</i> hemolysis</ins> <br><br>
      </h3>
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

<!-- 
---

<h1>
  Hemolysis is the Most Common Preanalytical Error
</h1>
<div class='columns'>
  <div class='columns-left'>
  </div>
  <div class='columns-right'>
  </div>  
</div> -->

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

<!-- ---

<h1>
  Blood Culture Contamination is Common
</h1>
<div class='columns'>
  <div class='columns-left'>
  </div>
  <div class='columns-right'>
  </div>  
</div> -->

---



<h1>
  Training and Feedback Synergistically Reduce Specimen Collection Error Rates
</h1>
<div class='columns'>
  <div class='columns-left'>
  </div>
  <div class='columns-right'>
  </div>  
</div>

<!-- 
---

<h1>
  Training and Feedback Reduce Contamination Rates
</h1>
<div class='columns'>
  <div class='columns-left'>
  </div>
  <div class='columns-right'>
  </div>  
</div> -->

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
      Estimating the costs and drivers of specimen hemolysis
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
    Estimating the costs and drivers of specimen hemolysis
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
  Study Design
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
    <table style='padding-left:20px;padding-bottom:10px;text-align:center;font-size:24px'>    
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
    &bull; Measured on Roche Cobas c702<br>
    &bull; Plasma samples<br>
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

<h1>
  Limitations to Cost Model
</h1>
<div class='columns'>
<div class='columns-left'>
  <ol>
    <li>
      Assumed redraw based on result 
    </li>
    <li>
      Did not account for indirect costs<br>
      - Patient harms due to missed or <br>&emsp;delayed diagnosis<br>
      - Physician and collector time
    </li>
  </ol>
</div>
<div class='columns-right'>
  <img src='./assets/iceberg.png' height=500>
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
      <img src='./assets/pareto_combined.png' width=500>
    </center>
  </div>
</div>

---

<h1>
  Significance of Pareto Principle
</h1>

<img src='./assets/targeted_training.png'>
<p style='margin-top:10px'>
  A targeted training and feedback campaign might offer greater efficiency and scalability
</p>
<p style='margin-top:20px'>
  <ins>
    Key Question:
  </ins>
</p>
<h3 style='border:solid;text-align:center;padding:10px;border-radius:10px;margin-top:0px'>
  Can we prospectively identify the outliers that are most important to train? 
</h3>

---

<h2>
  Pareto Principle and Power Laws
</h2>
<div class='columns'>
  <div class='columns-left'>
    <p>
      The Pareto Principle is often observed for processes that exhibit a power law<br>
    </p>
    <p>
      For a power law distributed data, mean and variance can be undefined<br>
    </p>
    <p style='margin-top:30px'>
      <ins>
        Significance<br>
      </ins>
    </p>
    <div style='border:solid;border-radius:10px;padding:10px;'>  
      <ul>
        <li>
          'Typical' cost is poorly defined<br>
        </li>
        <li>
          Difficult to define outliers
        </li>
      </ul>
    </div>
  </div>
  <div class='columns-right' style='margin-left:20px'>
      <img src='./assets/power_distribution.png' width=550 align='right'>
  </div>  

</div>

---

<h1>
  Power Laws Everywhere
</h1>
<div class='columns'>
  <div class='columns-left'>
    <p>
      Power law distributions arise in diverse artificial and natural systems
    </p>
    <p>
      Various generative mechanisms can give rise to power law phenomena
    </p>
    <ul><li>
      Some mechanisms are  random 
    </li></ul>
    <p>
      <ins>Key question</ins>
    </p>
    <div style='border:solid;border-radius:20px;padding:20px'>          
      Will the top 20% collectors continue to incur high costs in the future?
    </div>
  </div>
  <div class='columns-right'>
    <img src='./assets/power_laws_everywhere.png' width=550 style='margin-left:0px'>
    <p style='font-size:18px;text-align:right;margin-top:10px'>
      Newman, Mej. “Power Laws, Pareto Distributions and Zipf’s Law.” Contemporary Physics 46, no. 5 (September 2005): 323–51. https://doi.org/10.1080/00107510500052444.
    </p>
  </div>
</div>


---

<h1>
  Wisdom from ChatGPT-4
</h1>

<div style='margin-top:20px'>
  <ins>
    Prompt
  </ins><br>
  &emsp;Why do 20% of workers cause 80% of errors?
</div>
<div style='margin-top:40px'>
  <ins>
    Response
  </ins><br>
  <i>
    ... It's important to note that the 80/20 ratio is not a strict rule but a general observation. Identifying the underlying causes of errors and addressing them through training, process improvements, and accountability measures is essential for reducing errors within any organization.
  </i>
</div>


---

<h1>
  Part 1: Summary
</h1>
<div>
  <ol>
    <li>
      Annual insitution level hemlolysis redraw costs estimates approached $4,000,000 
    </li>
    <li>
      The majority of costs arise from the Emergency and Inpatient settings
    </li>
    <li>
      20% of collectors account for 80% of hemolysis costs across care settings
  </ol>
</div>

---


  <h3>
    Part 2
  </h3>
  <div style='border:solid;margin-left:0px;margin-right:40px;border-radius:20px;text-align:center;padding-top:10px;margin-left:10px'>
    <p style='padding-left:20px;'>
      Automated and objective dectection of underperforming specimen collectors
    </p>
  </div>  

---

<h1>
  <ins>
    Questions
  </ins>
</h1>
<div style='border:solid;border-radius:20px;padding:20px'>
  <ol>
    <li>
      Can we identify non-random variation in collector performance?
    </li>
    <li>
      If so, does it help us to predict future hemolysis costs?<br>
</div>

---

<h1>
  Analyzing Per Collector Hemolysis and Volumes
</h1>
<div class='columns'>
  <div class='columns-left' style='margin-top:10px'>
    <p>
      &bull; Median HI chosen as performance metric<br>
      &emsp; - Ranged from 0.0 to 534<br>
      &emsp; - Heavy tailed distribution<br>
      &emsp; - Wide variation for low volume collectors<br>
    </p>
    <p>
      &bull; Specimen volumes<br>
      &emsp; - Ranged from 1 to 4620<br>
      &emsp; - Heavy tailed distribution
    </p>
    <div style='margin-top:40px;border:solid;border-radius:20px;padding:20px;text-align:left'>
      <strong>Questions:</strong> <br>Is this all random performance variation?<br>Which collectors (if any) need training?
    </div>
  </div>
  <div class='columns-right'>
    <img src='./assets/joint_plot.png' width=700 style='margin-left:30px'>
  </div>  
<div>

---


<h3>
  Modeling Random Performance Variation among Equally Skilled Collectors
</h3>
<center>
  <img src='./assets/monte_carlo.png' width=900 style='margin-top:20px'>
</center>

---


<h2>
  Extrapolating Extreme p-values from Limited Simulations
</h2>
<div class='columns'>
  <div class='columns-left'>
    <div style='margin-left:20px'>
      &bull; Distribution of median hemolysis index is <br>&emsp;appproximately log-normal<br>
      <div style='border:solid;border-radius:20px;padding:10px;margin-top:80px'>
        <ol>
          <li>
            Run modest number of trials (500)<br>
          </li>
          <li>
            Fit log-normal model
          </li>
          <li>
            Extrapolate p-value from fitted distribution
          </li>
        </ol>
      </div>
    </div>
  </div>
  <div class='columns-right'>
    <center>
      <img src='./assets/lognormal_mc.png' width=325>
    </center>  
  </div>
</div>  


---

<h3 style='margin-bottom:30px'>
  Modeling Random and Nonrandom Variation in Collector Performance
</h3>
<img src='./assets/raw_triple_graph.png' style='margin-top:10px'>

---

<h2>
  Statistical Outliers Tend to Incur Higher Costs
</h2>
<center>
  <img src='./assets/double_graph.png' width=1000 style='margin-top:20px'>
</center>


---

<h2>
  Top 20% by Statistical Ranking Predicts Top 20% by Costs
</h2>
<div class='columns'>
  <div class='columns-left'>
    <img src='./assets/pred_true_rank.png' width=550 style='margin-left:20px'>
  </div>
  <div class='columns-right' style='margin-left:110px;margin-top:34px'>
    <table border="1" class="dataframe">
    <tbody>
      <tr>
        <th>Se</th>
        <td>0.69</td>
      </tr>
      <tr>
        <th>Sp</th>
        <td>0.92</td>
      </tr>
      <tr>
        <th>PPV</th>
        <td>0.69</td>
      </tr>
      <tr>
        <th>Accuracy</th>
        <td>0.88</td>
      </tr>
      <tr>
        <th>F1-Score</th>
        <td>0.69</td>
      </tr>
      <tr>
        <th>MCC</th>
        <td>0.61</td>
      </tr>
    </tbody>
  </table>
  </div>
</div>

---


<h1>
  Outlier Score is Predictive of Observed Costs
</h1>
<div class='columns'>
  <div class='columns-left' style='margin:10px'>
    The degree to which observed collector performance is 'unexpected' by a model of random variation among equally skilled collectors is highly predictive of costs
    <div style='margin-top:50px'>
  </div>
  <div class='columns-right'>
    <img src='./assets/regplot.png' width=500>
  </div>
</div>




---

<div>
  <ins> 
    Key question
  </ins>
</div>
<div style='border:solid;padding:20px;border-radius:20px;margin-top:5px'>
  Does the outlier score help to predict future hemolysis errors and costs?
</div>

<img src='./assets/forecasting.png' style='margin-top:50px'>

<!-- <div class='columns'>
  <div class='columns'>
  </div>
  <div class='columns'>

  </div>
</div> -->

---


<h2>
  Forecasting 2022 Costs Using December 2021 Data

<div>
  <div class='columns'>
  <div class='columns-left'>
    <img src='./assets/forecasting_double_left.png' width=500 >
  </div>
  <div class='columns-right'>
  <img src='./assets/forecasting_double_right.png' width=520 >

</div>
</div>


---

<h2>
  December 2021 Statistical Scores Predict 2022 20% Collectors
</h2>
<div class='columns'>
  <div class='columns-left'>
    <img src='./assets/pred_true_rank_forecasting.png' width=550 style='margin-left:20px'>
  </div>
  <div class='columns-right' style='margin-left:110px;margin-top:34px'>
    <table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Se</th>
      <td>0.48</td>
    </tr>
    <tr>
      <th>Sp</th>
      <td>0.87</td>
    </tr>
    <tr>
      <th>PPV</th>
      <td>0.48</td>
    </tr>
    <tr>
      <th>Accuracy</th>
      <td>0.79</td>
    </tr>
    <tr>
      <th>F1-Score</th>
      <td>0.48</td>
    </tr>
    <tr>
      <th>MCC</th>
      <td>0.35</td>
    </tr>
  </tbody>
</table>

<!-- 
---

<h3>
  Analyzing Annual Costs per Collector
</h3>
<div>
  Variation in collector costs poorly explained by: 
  <ol style='margin-top:10px'>
    <li>
      degree of hemolysis 
    </li>
    <li>
       # of specimen collected 
    </li>
  <or>
</div>

![bg right:55% width:500](./assets/baseplot.png) -->
<!-- 
---

<h3>
  Modeling Random Variation Among Equally Skilled Collectors
</h3>
<div>
  <p>
    &bull; Random variation modeled <br>&emsp;using monte carlo process<br>
  </p>
  <p>
    &bull; Random model describes <br>&emsp;central tendency in data<br>
  </p>
  <p>
    &bull; High cost collectors outside <br>&emsp;bounds of random model
  </p>
</p>

![bg right:55% width:500](./assets/baseplot_mc.png) -->

<!-- 
---

<h3>
  High Cost Collector Performance that is Unexpected by Random Model
</h3>
<div class='columns' style='margin-top:30px'>
  <div class='columns-left'>
    &bull; Monte-carlo model used to assign p-value<br>
    &bull; False discovery rate correction<br>
    &bull; Expectation values computed as -log(p)
    <br>
    <div style='border:solid;text-align:center;margin:10px;margin-top:50px;border-radius:20px;padding:20px'>
       Statistical model explains 71% of the variation in per collector costs
    </div>
  </div>
  <div class='columns-right'>
    <center>
      <img src='./assets/baseplot_regplot.png' width=400>
    </center>
  </div>
</div> -->



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

<!-- ---

<h1>
  Analyzing annual per collector data
</h1>
<div>
  &bull; High costs collectors tend to <br>&emsp;have higher hemolysis index<br>
  &bull; High costs collectors tend to <br>&emsp;collect more specimen<br>
</div>
<div style='margin-top:20px'>
  <ins>However:</ins><br>
  Selecting based on hemolysis index or number of specimen misses the high costs collectors
</div>

![bg right:55% width:650](./assets/gridplot_costs.png) -->

<!-- ---

<h3>
  Analyzing Variation in Median Hemolysis Index per Collector
</h3>
<div class='columns' style='margin-top:10px'>
  <div class='columns-left'>
    &bull; Median HI per collector varies widely<br>
    &bull; Variation lessens as # specimen increases<br>
    &bull; High costs collectors tend to have higher <br>&emsp;median HI and # specimens<br>
    &bull; Collectors with the highest median HI or # <br>&emsp;specimen captures low cost collectors<br>
    <div style='margin-top:40px;'>
      <ins>Hypothesis:</ins>
    </div>
    <div style='border:solid;padding:10px;margin:10px;border-radius:20px;text-align:center'>
      Much of the variation in collector performance reflects random variation among equally skilled collectors
    </div>
  </div>
  <div class='columns-right'>
    <img src='./assets/first_panel.png' width=500>
  </div>
</div> -->

---
