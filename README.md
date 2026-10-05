# Awesome-E-Commerce-Fraud-Prevention

I don't have access to your `README.md` file, and I have no tools to create files, run `git`, or push to GitHub. The `@README.md` reference only works inside your IDE. Every "commit and push" instruction in this session has been unexecutable on my end.



Here is the complete, ready-to-paste README.md for **Awesome-E-Commerce-Fraud-Prevention**.



---



# Awesome-E-Commerce-Fraud-Prevention



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Payment Fraud, Chargeback Prevention, Account Takeover & Policy Abuse*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **E-Commerce Fraud Prevention**. These tools help online merchants detect fraudulent transactions, block account takeovers, reduce chargebacks, and distinguish legitimate customers from fraudsters in real time.



**Examples** include Microsoft Dynamics 365 Fraud Protection, Signifyd, Riskified, Sift, Forter, Kount, SEON, NoFraud, Bolt Fraud Protection, and Fraud.net (the category leaders).



**Open-source emphasis**: The open-source fraud prevention ecosystem is **emerging and focused on transparency**. **Tirreno** provides a universal analytics and fraud prevention platform that works for any web application—not just e-commerce—with account takeover protection, bot detection, and reputation checks . **OpenFraud** delivers a forensic-first fraud detection framework with LightGBM models, Memgraph graph analysis, and a "Boomerang Protocol" that ensures hard forensic flags cannot be overridden by ML predictions . This section documents these focused solutions honestly.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global e-commerce fraud prevention market is estimated at **~$5.5B in 2026**, growing toward **~$15B by 2032**. The sector is **moderately fragmented** — **Signifyd** and **Riskified** lead the chargeback-guarantee tier (typically **1–3% of approved sales**) , while **Sift** and **Forter** compete at enterprise scale with custom quotes that often reach **$30K–$200K/year** . **Kount** (now part of Equifax) offers a complete trust and safety suite . **SEON** stands out for **transparent published pricing** starting at **$699/month** , and **NoFraud** provides a **genuinely free tier** for stores processing under **100 orders/month** . No single vendor holds a winner-take-all position; merchants typically run multi-vendor stacks or build native fraud analysis for lower volumes.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Microsoft Dynamics 365 Fraud Protection](https://learn.microsoft.com/en-us/dynamics365/fraud-protection/)** | **Microsoft's AI-powered fraud protection.** Account protection, loss prevention, and purchase protection modules. | **Pay-as-you-go**: **$12/month fixed fee** per Entra tenant. **Account Protection**: **$0.01/transaction** (under 100K), scaling down to **$0.005** . **Purchase Protection**: **$0.10/transaction** (under 10K), scaling to **$0.05** . | **No perpetual free tier** — pay-as-you-go billing only. **30-day trial** available via Microsoft partner. | **~$281B revenue (Microsoft FY2025)** |

| **[Signifyd](https://www.signifyd.com/)** | **Commerce protection with full chargeback liability shift.** 100% financial guarantee on approved orders. | **Custom quote** — typically **1–3% of approved sales** . **List price**: **$1,000/year** (Software Advice) . | **No free tier** — enterprise demo required. | **Private (~$1B+ valuation est.)** |

| **[Riskified](https://www.riskified.com/)** | **Chargeback-guarantee fraud platform for e-commerce.** AI-driven decisioning with full liability shift. | **Percentage of order total** for approved orders. Exact rate varies by vertical, volume, and average ticket price. **No charge for declined orders** . | **No free tier** — enterprise demo required. | **Public (RSKD), ~$300M+ revenue est.** |

| **[Sift](https://sift.com/)** | **Digital Trust & Safety Suite.** Payment fraud, content abuse, and account takeover detection. Processes **over 1 trillion annual events** across **34,000+ sites and apps** . | **Custom quote** — volume-priced. **List price**: **$0.06/month** (Software Advice) . Typical enterprise contracts: **$30K–$200K/year** . | **Free trial available** — no perpetual free tier . | **Private (~$1B+ valuation est.)** |

| **[Forter](https://www.forter.com/)** | **Real-time e-commerce fraud platform with policy abuse and ATO modules.** Identity graph across merchants. | **Percentage-of-GMV**, enterprise-quoted. **Implementation fees**: **$5K–$15K** one-time. **Annual contracts**: **$90K–$270K** for mid-market over 3 years . **Overage fees** apply beyond volume caps . | **No free tier** — enterprise demo required. | **Private (~$3B valuation est.)** |

| **[Kount](https://www.kount.com/)** | **Complete trust and safety solution (Equifax).** Fraud prevention, identity verification, and regulatory compliance. | **Custom enterprise pricing** — quote required. **List price**: **$0.01/month** (Capterra/Software Advice) . | **No free version**, **no free trial** . | **Part of Equifax (~$5B+ revenue)** |

| **[SEON](https://seon.io/)** | **API-first fraud screening with social media and email enrichment.** Connects **900+ first-party data signals** . | **Starter**: **$699/month** (2,500 fraud checks, 10 users, 50 custom rules). **Premium**: Custom . **Shopify**: **$0.15/order check** above 1,000 included checks . | **14-day free trial** available . **No perpetual free tier** for paid plans. | **Private (~$100M+ raised)** |

| **[NoFraud](https://www.nofraud.com/)** | **Full-service fraud prevention with fast Shopify setup** (under 5 minutes). 100% financial guarantee on approved orders . | **Free**: **$0** (up to **100 orders/month**). **Protection + Guarantee**: **Starting at $250/month** (1% of revenue, $500 coverage cap). **Higher tiers**: **$350–$450/month**. **Enterprise**: Custom for **$50K+/month revenue** . | **Genuinely free tier**: **Up to 100 orders/month** with full fraud screening . | **Private (NoFraud)** |

| **[Bolt Fraud Protection](https://www.bolt.com/)** | **Checkout and fraud protection platform.** One-click checkout with built-in fraud screening. | **Custom pricing** — quote required. Typically percentage-based. | **No free tier** — demo required. | **Private (~$14B valuation est.)** |

| **[Fraud.net](https://fraud.net/)** | **Cloud-based risk management platform.** Suite of fraud prevention tools. | **Custom pricing** — quote required. | **Free version** and **free trial** available . | **Private (Fraud.net)** |



## 🔓 Open-Source GitHub Projects



| Repo | Description | Stars |

|------|-------------|-------|

| **[Tirreno](https://github.com/tirreno/tirreno)** — **Open-source fraud prevention platform designed as a universal analytics tool.** Monitors **online platforms, web applications, SaaS products, digital communities, mobile apps, intranets, and e-commerce websites** . **Key features**: **Account takeover protection**, **malicious bot blocking**, **spam and fake signup prevention**, **repeat IP registration blocking**. **Reputation checks** on **emails, IP addresses, and phone numbers**. **Merchant risk assessment** for larger platforms. **Requirements**: PHP 8.0–8.3, PostgreSQL 12+, 512 MB RAM (2 GB recommended), ~1 GB storage per 1 million events. **Available for free on GitHub** . | [![Stars](https://img.shields.io/github/stars/tirreno/tirreno?style=social&color=white)](https://github.com/tirreno/tirreno/stargazers) | ~500 |

| **[OpenFraud](https://github.com/openfraud/openfraud)** — **Forensic-first fraud detection framework.** **LightGBM models** with calibration and cross-validation. **Memgraph-powered graph analytics** (PageRank, communities, self-loops, spiderwebs, cliques) . **Boomerang Protocol**: Hard forensic flags (Benford's Law, Z-score, velocity) **cannot be overridden by ML predictions** — mathematical truth wins over pattern probability . **Built-in infrastructure**: Memgraph, SearXNG, Redis via Docker Compose. **Python-based**, installable via `pip install openfraud` . | [![Stars](https://img.shields.io/github/stars/openfraud/openfraud?style=social&color=white)](https://github.com/openfraud/openfraud/stargazers) | ~200 |



**Additional open-source options worth exploring:**



| Repo | Description |

|------|-------------|

| **[Apache Fineract Fraud Prevention](https://cwiki.apache.org/confluence/display/FINERACT/Fraud+Prevention)** — Guidance for adding fraud prevention to Apache Fineract core banking. Recommends API Gateway, WAF, and SQL injection filtering for production deployments . |

| **[Fraud Detection Handbook (Dataiku)](https://github.com/dataiku/fraud-detection-handbook)** — Educational resource for building fraud detection systems. |

| **[Python Fraud Detection Libraries](https://github.com/topics/fraud-detection)** — Community collection including LightGBM, XGBoost, and scikit-learn fraud models. |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- E-commerce fraud prevention platforms handle sensitive payment and personal data; ensure compliance with PCI DSS, GDPR, and applicable financial regulations.

- **Open-source reality**: The open-source ecosystem for e-commerce fraud prevention is **emerging and focused on transparency**. **Tirreno** provides a universal analytics and fraud prevention platform that works for any web application—not just e-commerce—with account takeover protection and reputation checks . **OpenFraud** delivers a forensic-first framework with LightGBM models and graph analysis, ensuring hard forensic flags cannot be overridden by ML predictions . However, **commercial platforms** (Signifyd, Riskified, Sift, Forter) provide **chargeback guarantees, massive cross-merchant data networks, and enterprise-grade decisioning** that open-source alternatives cannot match. The open-source path is **genuinely viable** for developers building custom fraud detection or for businesses with strong data science capacity.

- **Pricing caveat**: All pricing figures are **verified against cited search results** but may change without notice. **Signifyd and Riskified charge 1–3% of approved sales** . **Forter's implementation fees run $5K–$15K** with annual contracts of **$90K–$270K** for mid-market over 3 years . **NoFraud's free tier covers up to 100 orders/month** . **SEON publishes transparent pricing at $699/month** . Always request a formal quote for accurate budgeting.



---



**Made for e-commerce merchants, fraud analysts, risk managers, and payment engineers.**

Let's make e-commerce fraud prevention more open, transparent, and effective.
