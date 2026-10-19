# Cell-to-Cell Communication: Pituitary Gonadotroph Signaling to Ovarian Granulosa Cells

## Biological Question

How does a pituitary gonadotroph communicate with ovarian granulosa cells through Follicle-Stimulating Hormone (FSH) signaling to regulate ovarian follicle development?

* * *

# Chosen Sender Cell and Biological Context

The selected sender cell is the **Pituitary Gonadotroph**, an endocrine cell found in the anterior pituitary gland. Pituitary gonadotrophs produce reproductive hormones that regulate ovarian and testicular function. In this communication model, the biological context is female reproductive physiology, specifically ovarian follicle growth and maturation. These cells communicate with ovarian target cells through endocrine signaling by releasing hormones into the bloodstream.

* * *

# Candidate Ligand and Evidence for Sender-Cell Expression

The candidate ligand identified is **Follicle-Stimulating Hormone (FSH)**.

FSH is produced by pituitary gonadotroph cells and is essential for regulating ovarian follicular growth and development. The **FSHB** gene encodes the beta subunit of Follicle-Stimulating Hormone and serves as a marker of gonadotroph function.

### Evidence

Human Protein Atlas and UniProt indicate expression and function of the FSHB gene in pituitary endocrine cells. FSH is a glycoprotein hormone involved in reproductive regulation and follicle development.

**Ligand:** Follicle-Stimulating Hormone (FSH)

**Gene:** FSHB

* * *

# Receptor and Receiver Cell with Supporting Evidence

The receptor selected is the **Follicle-Stimulating Hormone Receptor (FSHR)**.

The receiver cell is the **Ovarian Granulosa Cell**. Granulosa cells express FSHR and respond directly to FSH stimulation. Activation of FSHR promotes follicular growth, estrogen production, and maturation of ovarian follicles.

### Evidence

Human Protein Atlas data support expression of FSHR in ovarian tissue. Granulosa cells are recognized biological targets of FSH signaling.

**Receptor:** FSHR

**Receiver Cell:** Ovarian Granulosa Cell

* * *

# Type of Cell-to-Cell Signaling

This communication pathway represents **Endocrine Signaling** because FSH is released by pituitary gonadotrophs into the bloodstream and acts on distant target cells in the ovary.

* * *

# OmniPath Findings

OmniPath identified a ligand-receptor interaction between **FSHB** and **FSHR**. The interaction is supported by multiple databases, including CellCall, CellChatDB, and other curated signaling resources.

This finding supports the proposed endocrine communication pathway in which FSH produced by pituitary gonadotrophs binds to FSHR expressed on ovarian granulosa cells.

### Insert OmniPath Screenshot Below

images/03\_omnipath\_evidence.png

* * *

# STRING Network Interpretation

A STRING protein interaction network was generated using FSHR and associated signaling proteins.

## Key Proteins

-   FSHR
-   GNAS
-   ADCY5
-   PRKACA
-   CREB1
-   AKT1
-   MAPK1

## Functional Significance

### FSHR

Receives the extracellular FSH signal.

### GNAS

Couples receptor activation to intracellular signaling.

### ADCY5

Produces cyclic AMP (cAMP).

### PRKACA

Mediates Protein Kinase A signaling.

### CREB1

Regulates transcription of genes involved in follicular development.

### AKT1

Promotes cell survival and growth.

### MAPK1

Regulates cell proliferation and differentiation.

## Enriched Pathway

The most relevant enriched pathway identified in STRING was the **cAMP signaling pathway**, which is activated downstream of FSHR and contributes to follicular maturation and estrogen synthesis.

### Insert STRING Network Screenshot Below

images/05\_string\_network.png

### Insert STRING Enrichment Screenshot Below

images/06\_string\_enrichment.png

* * *

# IntAct Validation

A protein interaction associated with the FSHR signaling pathway was examined using IntAct.

### Interaction Examined

PRKACA - PRKAR1A

### Organism

Homo sapiens

### Detection Method

Anti-tag Co-Immunoprecipitation (anti-tag coIP)

### Interaction Type

Direct Interaction

### Supporting Publication

PMID: 24855271

### Interpretation

The interaction between PRKACA and PRKAR1A provides experimental evidence supporting the Protein Kinase A signaling pathway. Since PKA functions downstream of FSHR-mediated cAMP production, this interaction strengthens the proposed signaling mechanism leading to granulosa cell activation.

### Insert IntAct Screenshot Below

images/07\_intact\_evidence.png

* * *

# Questions to Answer

## 1\. What sender cell did you choose, and in what tissue or biological context does it act?

I selected the Pituitary Gonadotroph as the sender cell. It is located in the anterior pituitary gland and functions in reproductive regulation through hormone secretion. The biological context is ovarian follicle development.

## 2\. What signaling molecule did you identify, and what evidence supports its production by the sender cell?

The signaling molecule is Follicle-Stimulating Hormone (FSH). Expression of the FSHB gene in pituitary gonadotroph cells provides evidence for FSH production.

## 3\. What receptor receives the signal, and which receiver cell did you select?

The receptor is FSHR, and the receiver cell is the ovarian granulosa cell because granulosa cells express FSHR and respond to FSH stimulation.

## 4\. What type of cell-to-cell signaling is represented?

This pathway represents endocrine signaling because the signal travels through the bloodstream to a distant target organ.

## 5\. Which proteins in your STRING network appear most relevant to the receptor-associated response?

GNAS, ADCY5, PRKACA, CREB1, AKT1, and MAPK1 are the most relevant proteins because they transmit signals downstream of FSHR activation and regulate growth, survival, and gene expression.

## 6\. What enriched pathway or biological process is consistent with your proposed mechanism?

The cAMP signaling pathway is most consistent with the proposed mechanism because FSHR activates adenylate cyclase, resulting in cAMP production and activation of Protein Kinase A signaling.

## 7\. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

IntAct identified a direct interaction between PRKACA and PRKAR1A in Homo sapiens. The interaction was supported by anti-tag co-immunoprecipitation experimental evidence and a published study (PMID: 24855271).

## 8\. Which parts of your final model are strongly supported, and which parts remain an inference?

Strongly supported components include:

-   Production of FSH by pituitary gonadotrophs
-   Binding of FSH to FSHR
-   Expression of FSHR in granulosa cells
-   Activation of cAMP signaling

Inferential components include some downstream signaling relationships among AKT1, MAPK1, CREB1, and other proteins identified through network analysis.

## 9\. What cellular response is expected in the receiver cell, and why?

The expected response is granulosa-cell proliferation, estrogen synthesis, and ovarian follicular maturation because activation of FSHR stimulates intracellular pathways involved in growth, differentiation, and hormone production.

* * *

# Final Cell-to-Cell Communication Model

```plaintext
Pituitary Gonadotroph
          │
          ▼
         FSH
          │
     Bloodstream
          │
          ▼
Ovarian Granulosa Cell
          │
         FSHR
          │
          ▼
         GNAS
          │
          ▼
        ADCY5
          │
          ▼
         cAMP
          │
          ▼
       PRKACA
          │
          ▼
        CREB1
       /      \
    AKT1     MAPK1
       \      /
          ▼
Follicular Development
Estrogen Production
Granulosa Cell Proliferation
```

* * *

# Interpretation (196 Words)

This model describes endocrine communication between a pituitary gonadotroph and an ovarian granulosa cell. The sender cell, the pituitary gonadotroph, synthesizes and secretes Follicle-Stimulating Hormone (FSH), a hormone involved in regulating female reproductive function. After secretion, FSH enters the bloodstream and travels to the ovary, where it binds to the Follicle-Stimulating Hormone Receptor (FSHR) expressed on granulosa cells. Receptor activation initiates intracellular signaling through G proteins, particularly GNAS, which activates adenylate cyclase and increases cyclic AMP (cAMP) production. Elevated cAMP activates Protein Kinase A (PRKACA), resulting in phosphorylation of downstream transcription factors such as CREB1. Additional signaling proteins including AKT1 and MAPK1 contribute to cellular survival, proliferation, and differentiation. These signaling pathways collectively promote granulosa-cell growth, estrogen synthesis, and maturation of ovarian follicles. OmniPath supports the ligand-receptor interaction between FSH and FSHR, while STRING identifies functionally related proteins associated with downstream signaling events. IntAct provides experimental evidence supporting protein interactions within the Protein Kinase A pathway. Overall, the evidence supports an endocrine signaling model in which pituitary gonadotrophs regulate ovarian follicle development through FSH-mediated activation of FSHR and downstream intracellular signaling pathways.

* * *

# References and Database Links

Human Protein Atlas
https://www.proteinatlas.org/

UniProt
https://www.uniprot.org/

OmniPath Explorer
https://explore.omnipathdb.org/

STRING Database
https://string-db.org/

IntAct Molecular Interaction Database
https://www.ebi.ac.uk/intact/

