---
title: Endocrine System Overview
tags: [InProgess, Endocrine]
feed: "show"
---

# Overview

- How organs and tissues communicate with each other
- Allows organisms to respond to changes in internal and external stimuli to maintain homeostasis
- Relies on hormonal communication
- Influenced by and influences the nervous system

```mermaid
graph TD
%% ===== HYPOTHALAMUS =====
H[Hypothalamus]

%% ===== PITUITARY =====
AP[Anterior Pituitary]
PP[Posterior Pituitary]

%% ===== TARGET GLANDS =====
T[Thyroid Gland]
A[Adrenal Cortex]
O[Ovaries]
L[Leydig Cells]
S[Sertoli Cells]
LIV[Liver]
M[Mammary Glands]
AC[Adrenal Cortex]

%% ==== AP HORMONES ====
FSH([FSH])
LH([LH])
ACTH([ACTH])
TSH([TSH])
Pr([Prolactin])
En([Endorphins])
GH([GH])


%% ===== PERIPHERAL HORMONES =====
T3((T₃))
T4((T₄))
CORT((Cortisol))
E((Estrogen))
P((Progesterone))
TST((Testosterone))
GH((GH))
IGF((IGF-1))
PRL((Prolactin))
OX((Oxytocin))
ADH((ADH))
GC((Glucocorticoids))
En((Endorphins))
GH((Growth Hormones))
Som((Somatostatin))


%% ==== PROCESSES ====
OO[/Oogenesis/]
Sp[/Spermatogenesis/]

Ov([Ovulation])


%% ==== HPG Axis ====
H -->|GnRH|AP

AP-->FSH-->S
S -->Sp
AP -->LH-->L
L -->TST

AP -->FSH-->O
AP -->LH-->Ov
O --> E
O --> P

%% ==== HPA Axis ====
H -->|CRF|AP
AP -->|ACTH|AC
AC --> GC

AP -->En
GC -.-xEn

%% ==== HPT Axis ====
H --> |TRH| AP
AP --> |TSH| T
T --> T3
T --> T4
T4 --> T3

%% ==== Prolactin ====
H -->|PIF|AP
AP -->|Prolactin| M

%% ==== Growth Hormone ====
H -->|GHRH|AP
AP -->GH

H -->Som-.-x GH

```

# Other Stuff

The endocrine system is one way that organs **communicate** with each other. "Endo" means *inside* and "crine" comes from the Greek root "kreinin", which in this case, means "to secrete".

- This system deals with **hormones** which are *secreted* into the **bloodstream**

## General Definitions

- **[[Gland]]**: an organ that *secretes* hormones
- **[[Hormones|Hormone]]**: a *chemical* messenger that is secreted into the bloodstream

## [[Hormones]]

Hormones are the *messengers* of the endocrine system. Hormones are classified based on

1. Their makeup

- [[Peptide Hormones]]
- [[Amino Acid-Derived Hormones]]
- [[Steroid Hormones]]

2. Their intended action

- **[[Tropic Hormones]]** act on a *gland* to secrete a hormone
- **[[Direct Hormones]]** act on the *target tissue*

## The big players: hypothalamus and pituitary

Many endocrine axes start at the **[[hypothalamus]]**, which secretes [[Endocrine System/Peptide Hormones|peptide hormones]] that act on the [[anterior pituitary]].

- These are [[tropic hormones]]

The hypothalamus also [[Action Potentials|electrically stimulates]] the [[posterior pituitary]].

## [[Endocrine System/Pituitary Gland|Pituitary Gland]]

The pituitary gland has two lobes: the ***anterior** pituitary* and the ***posterior** pituitary*. How the hypothalamus sends the signal depends on which lobe the axis utilizes.

### [[Endocrine System/Anterior Pituitary|Anterior Pituitary]]

The [[Endocrine System/Anterior Pituitary|anterior pituitary]] (AP) is made of [[Gland|glandular]] tissue that can both synthesize and secrete [[Endocrine System/Peptide Hormones|peptide hormones]]. The hypothalamus releases ***releasing*** and ***inhibiting*** factors into the ***[[Hypophyses|hypophyseal]] [[Portal System|portal system]]***.  

- Hypothalamus sends ==[[Gland#Types of Glands|endocrine]] hormones to anterior pituitary==

#### Axes Involving Anterior Pituitary

##### Tropic Hormones

- [[Endocrine System/Reproductive Axis|HPG Axis]]
  - AP hormones: **[[Follicle Stimulating Hormone (FSH)]]** and **[[Lutenizing Hormone (LH)]]**
  - [[Gonadotropin Releasing Hormone (GnRH)]] --> FSH + LH --> [[Androgens]]
- [[Endocrine System/HPA Axis|HPA Axis]]
  - [[Corticotropin Releasing Factor (Hormone)]] --> [[Adrenocorticotropic Releasing Hormone (ACTH)]] --> [[Glucocorticoids]]
- [[Endocrine System/Thyroid Axis|HPT Axis]]
  - TRH --> TSH --> T3 + T4

##### Direct Hormones

- [[Prolactin]]
  - PIF (Dopamine) --| Prolactin
- [[Endorphins]]
  - CRH --> Endorphins
  - Glucocorticoids --| Endorphins
- [[Growth Hormone]]
  - GHRH --> GH
  - Somatostatin --| GH

| Hypothalamic Hormone | AP Hormone | Target Tissue          | Effect          |
| -------------------- | ---------- | ---------------------- | --------------- |
| GnRH                 | FSH        | Ovaries, Sertoli cells |                 |
|                      | LH         |                        |                 |
| CRF                  | ACTH       | Adrenal cortex         | glucocorticoids |
| TRH                  | TSH        |                        |                 |

### [[Endocrine System/Posterior Pituitary|Posterior Pituitary]]

The [[Endocrine System/Posterior Pituitary|posterior pituitary]] only *stores* hormones that the *hypothalamus produces*. The hypothalamus sends axons down into the posterior pituitary. When depolarized, the posterior pituitary releases the hormones (known as **neurohormones**) from the [[Neuron Structure|axon terminals]].

[[Anti-Diuretic Hormone (ADH)]]
[[Oxytocin]]

## Target Tissues

### [[Adrenal Gland]]

### [[Renal Hormones]]

### [[Pancreatic Hormones]]

[[Endocrine System/Renin-Angiotenisin-Aldosterone System|Renin-Angiotensin-Aldosterone System]]
[[Catecholamines]]

[[Parathyroid Gland]]

Appetite hormones
[[ghrelin]]
[[leptin]]
[[somatostatin]]

[[pineal gland]]
[[thymus]]

[[anp]]

[[Digestion]]
[[Gastrin]]
[[Cholecystekinin]]

whether the axis uses the [[Public/Endocrine System/Anterior Pituitary|anterior pituitary]] or the [[Public/Endocrine System/Posterior Pituitary|posterior pituitary]].
