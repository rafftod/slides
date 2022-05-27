---
marp: true
theme: raptus
paginate: true
class: lead
footer: "Raffaele Todesco - Swarm Intelligence"
---

<!-- paginate: false -->
<!-- class: lead -->

# Swarm Intelligence

## Project presentation

---

<!-- paginate: true -->
<!-- class: default -->

## Problem definition

-   Collective foraging in an heterogeneous swarm of robots
-   3 types of robots :
    -   **CamBots** : can see the objects
    -   **GroundBots** : can detect the nest
    -   **LightBots** : can detect light

![bg right:45% w:70%](arena.png)

---

## Proposed solution

-   All robot behaviours modeled as FSMs
-   Static division of labor due to heterogeneous capabilities :
    -   **CamBots** : look for objects and bring them to the nest
    -   **GroundBots** : signal the nest
    -   **LightBots** : signal the light source
-   Control software designed with a swarm of 8 CamBots, 5 GroundBots and 3 LightBots

---

## CamBots behaviour

![height:50%](https://mermaid.ink/img/pako:eNqF0j1PwzAQBuC_cvLA1C6MGZhaiQEBglYsWQ7fNTV1bMsfIFT1v3NuUtpUQmRJ5Dx-fWd7r7QnVo1KGTMvDHYR-_nnbetAnuMgtGrtrEdighd05Ht4Q7trFWCCEr-m9OEPaK_hPSMZ18HKw9P7B-s8uG32U_ds9K66dZi4UKZsEX0I1V0iGrOkSpjP72o4NKMA4iwvpoHUX5WEImJVYuQMJgFa0znp5wb8MEvGtPWJgZ0v3XY6ua5zzjcJQ2CMpyUk-owe_WUixmiumL3MEhNkH6SQEgZlx5b-Szs5qp0vjzXLnnFIkAI78Q4cpzxgumzjd0dD9JqpRK7hqWjNKW2KVTPVc-zRkFyffQ1oVd5yz61q5JMwytG37iCuBJJTWpLJPqpmgzbxTGHJ_vXbadXkWPiExis4qsMP7XbcAA)

---

## GroundBots and LightBots behaviour

![bg h:30% w:170%](https://mermaid.ink/img/pako:eNp10bFuwyAQANBfOTE1Urx4RG2GKu3YoamUheViLg4KHBbgWFGUf-_FdtV6KBPi3h3ccVNNtKS0ygULbR22CUN1qQ2DrPEQjPpEtjHAHv3ZKMAMaViCnWsZPXxQLhPIvARblztKmaao7aZoGqCqNoJBw6vH5gxHH2MCJ4QKNYXsXIZHaDuBXzFCQL4Ck2tPh9inDE-bejVJIQ8plTW807BAzy_1CqQV4AiH3-sWieNb_k38k6XWKlAK6KxM7_aoYVQ5UZAWtWwtJpmV4bu4vrMyhTfriqTpI_pMa4V9ibsrN0qX1NMPmn9gVvdv8xmFaA)

![bg h:20% w:140%](https://mermaid.ink/img/pako:eNpVkLlywkAMhl9Foxo3lFtQJV2GIhQ02whL2DvZg1nJEIbh3bOxTYEqHZ9-HQ_sCws6VCOTj0BDpdRdtz5DszkJHr8pc0lwpPjjEUih3t6BQxgyRfgKw2gLoXEh6g26btdCcEsZQjbJGuwOQYFO5SpgYxUdS-RVNc49rdXBfkonqVDOoPOMGPLQxspFQX57ERbGDSapiQK3Ox7_Eh5tlCQeXXOZatva52fjpgu3hT85WKnozhRVNkiTlcM99-isTvKC1l-s1PMP3KNjmg)

---

<!-- class: lead -->

# Results

---

<!-- class: default -->

## Flexibility

![auto](flexibility.png)

---

## Scalability

![h:60% w:80%](scalability.png)

---

## Conclusion

-   Larger swarms do not always yield better results
-   CamBots are the key performance drivers
-   Physical interference is a real problem
-   Reality gap is not faced yet

---

<!-- class: lead -->

# Questions ?
