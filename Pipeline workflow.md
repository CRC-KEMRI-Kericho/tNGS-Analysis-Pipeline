#Targeted Next Generation Sequencing (tNGS)

TB targeted next-generation sequencing is a molecular drug-susceptibility testing approach that uses massively parallel sequencing of selected Mycobacterium tuberculosis genomic regions associated with antimicrobial resistance, often directly from clinical specimens, followed by variant detection and interpretation against validated resistance catalogues to predict susceptibility or resistance to multiple anti-TB drugs simultaneously.


## Analysis Workflow

<img width="1536" height="1024" alt="tNGS_workflow" src="https://github.com/user-attachments/assets/0430b32e-b13c-4e5a-a9e4-0ec902e9ff78" />

# Summary Report

------------------------------------------------------------------------

## 1. SAMPLE & TEST INFORMATION

  Field                     Result
  ------------------------- -----------------------------------------------
  **Laboratory ID**         TB-TNGS-DEMO-001
  **Specimen type**         Sputum
  **Test**                  TB targeted next-generation sequencing (tNGS)
  **Sequencing platform**   Illumina NextSeq
  **MTB detected**          **DETECTED**
  **Analysis status**       **PASS**
  **Report type**           Demonstration

------------------------------------------------------------------------

## 2. DRUG-RESISTANCE SUMMARY

  -----------------------------------------------------------------------
  Drug                    Relevant variant        Interpretation
  ----------------------- ----------------------- -----------------------
  **Rifampicin**          *rpoB* S450L            **Resistant**

  **Isoniazid**           *katG* S315T            **Resistant**

  **Levofloxacin**        *gyrA* D94G             **Resistant**

  **Moxifloxacin**        *gyrA* D94G             **Resistant**

  **Amikacin**            No validated resistance **No resistance
                          mutation                detected**

  **Bedaquiline**         No validated resistance **No resistance
                          mutation                detected**
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 3. RESISTANCE-ASSOCIATED MUTATIONS

  ------------------------------------------------------------------------------------
  Gene       Mutation   Associated              Allele     Read depth Interpretation
                        drug(s)              frequency                
  ---------- ---------- --------------- -------------- -------------- ----------------
  *rpoB*     S450L      Rifampicin           **98.7%**     **1,842×** Resistance
                                                                      associated

  *katG*     S315T      Isoniazid            **99.2%**     **2,105×** Resistance
                                                                      associated

  *gyrA*     D94G       Levofloxacin;        **97.6%**     **1,764×** Resistance
                        Moxifloxacin                                  associated
  ------------------------------------------------------------------------------------

**Interpretation source:** WHO Catalogue of mutations in *Mycobacterium
tuberculosis* complex and their association with drug resistance.

------------------------------------------------------------------------

## 4. SEQUENCING & ANALYSIS QUALITY CONTROL

  -----------------------------------------------------------------------------------
  QC indicator                            Number           Percentage Status
  ------------------------- -------------------- -------------------- ---------------
  **Total sequencing               **1,842,516**           **100.0%** **PASS**
  reads**                                                             

  **Reads passing QC**             **1,731,964**            **94.0%** **PASS**

  **Reads mapped to H37Rv**        **1,693,022**           **97.8% of **PASS**
                                                   QC-passing reads** 

  **Mean target coverage**            **1,245×**                  N/A **PASS**

  **Resistance targets               **12 / 12**           **100.0%** **PASS**
  adequately covered**                                                

  **Resistance-associated                  **3**                  N/A ---
  mutations detected**                                                

  **Overall sequencing and                   ---                  --- **PASS**
  analysis QC**                                                       
  -----------------------------------------------------------------------------------

**Reference genome:** *Mycobacterium tuberculosis* H37Rv (NC_000962.3)

**QC assessment:** Sequencing, mapping and target coverage met the
demonstration requirements for downstream resistance-mutation
interpretation.

------------------------------------------------------------------------

## 5. FINAL INTERPRETATION

### DRUG-RESISTANT TB PROFILE PREDICTED

Targeted NGS detected resistance-associated mutations in *rpoB*, *katG*
and *gyrA*, predicting resistance to **rifampicin, isoniazid,
levofloxacin and moxifloxacin**.

No validated resistance-associated mutation was detected for amikacin or
bedaquiline in the reported, adequately covered targeted regions.

Results should be interpreted according to the validated tNGS assay, the
WHO mutation catalogue, applicable national TB diagnostic algorithms,
clinical information and, where required, complementary phenotypic
drug-susceptibility testing.

------------------------------------------------------------------------


**Reference genome:** H37Rv NC_000962.3\
**Interpretation resource:** WHO TB Mutation Catalogue\
**Pipeline status:** **PASS**

------------------------------------------------------------------------

**Report status:** **DEMONSTRATION ONLY --- NOT FOR CLINICAL USE**
