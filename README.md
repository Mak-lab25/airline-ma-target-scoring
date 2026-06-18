# ✈️ Airline M&A Target Scoring — Excel Business Case

> **Français** | [English below](#-airline-ma-target-scoring--excel-business-case-1)

---

## 🇫🇷 Contexte

Ce projet est un cas pratique d'analyse financière développé dans le cadre de mon expérience chez **British Airways**, où j'analysais des indicateurs financiers et opérationnels pour soutenir la prise de décision.

L'objectif : **recommander la meilleure cible d'acquisition** parmi 8 compagnies aériennes low-cost européennes, en construisant un modèle de scoring multi-critères entièrement sous Excel.

---

## 🎯 Problématique

> *British Airways souhaite acquérir une compagnie aérienne low-cost européenne. Quelle est la cible la plus attractive ?*

Les compagnies analysées : **Ryanair, EasyJet, Wizz Air, Norwegian, Pegasus, Vueling, Transavia, Jet2**

---

## 🔍 Approche analytique

### 1. Dimensions d'analyse
| Dimension | KPIs clés |
|---|---|
| **Rentabilité** | Marge bénéficiaire, ROA |
| **Cash** | Ratio cash/profit (cash conversion) |
| **Risque financier** | Ratio Dette/Actifs, Current Ratio |
| **Croissance** | Taux de croissance, pays desservis |
| **Valorisation** | EV/Revenue |
| **Opérations** | Load factor, taux de ponctualité, satisfaction client |

### 2. Fonctions Excel utilisées
`SI` · `ET` · `OU` · `NB.SI` · `SOMME.SI` · `RECHERCHEX` · Tableaux croisés dynamiques · Graphiques · Mise en forme conditionnelle

### 3. Scoring composite
Chaque KPI est normalisé sur 100, puis pondéré pour produire un **score d'attractivité global** par compagnie.

---

## 📊 Structure du fichier

| Onglet | Contenu |
|---|---|
| `Business_Case` | Énoncé et instructions |
| `Financials` | Données financières brutes (8 compagnies) |
| `Market` | Croissance, présence géographique, scores digitaux |
| `Operations` | Ponctualité, satisfaction, load factor |
| `Analysis` | KPIs calculés, normalisation, scoring |
| `Monthly_Performance` | Revenus et performances mensuels 2021 |
| `Risk_Lookup` | Table de référence des niveaux de risque |

---

## 🏆 Compétences démontrées

- Modélisation financière sous Excel (M&A screening)
- Construction d'un scoring multi-critères pondéré
- Analyse de données opérationnelles et financières
- Visualisation et dashboard exécutif
- Fonctions avancées Excel (RECHERCHEX, TCD, formules imbriquées)

---

---

# ✈️ Airline M&A Target Scoring — Excel Business Case

> **English** | [Français ci-dessus](#️-airline-ma-target-scoring--excel-business-case)

---

## 🇬🇧 Context

This project is a financial analysis case study built on work carried out during my time at **British Airways**, where I analysed financial and operational indicators to support business decision-making.

The goal: **recommend the best acquisition target** from 8 European low-cost carriers, using a multi-criteria scoring model built entirely in Excel.

---

## 🎯 Business Problem

> *British Airways wants to acquire a European low-cost airline. Which target is the most attractive?*

Companies analysed: **Ryanair, EasyJet, Wizz Air, Norwegian, Pegasus, Vueling, Transavia, Jet2**

---

## 🔍 Analytical Approach

### 1. Analysis Dimensions
| Dimension | Key KPIs |
|---|---|
| **Profitability** | Profit margin, ROA |
| **Cash** | Cash conversion ratio |
| **Financial risk** | Debt/Assets ratio, Current Ratio |
| **Growth** | Growth rate, countries served |
| **Valuation** | EV/Revenue |
| **Operations** | Load factor, on-time rate, customer rating |

### 2. Excel Functions Used
`IF` · `AND` · `OR` · `COUNTIF` · `SUMIF` · `XLOOKUP` · Pivot Tables · Charts · Conditional Formatting

### 3. Composite Scoring
Each KPI is normalised to a 0–100 scale, then weighted to produce an **overall attractiveness score** per company.

---

## 📊 File Structure

| Sheet | Content |
|---|---|
| `Business_Case` | Problem statement and instructions |
| `Financials` | Raw financial data (8 companies) |
| `Market` | Growth rates, geographic reach, digital scores |
| `Operations` | On-time performance, customer satisfaction, load factor |
| `Analysis` | Calculated KPIs, normalisation, scoring |
| `Monthly_Performance` | Monthly revenue and performance data (2021) |
| `Risk_Lookup` | Risk level reference table |

---

## 🏆 Skills Demonstrated

- Financial modelling in Excel (M&A screening)
- Multi-criteria weighted scoring model
- Financial and operational data analysis
- Executive dashboard and data visualisation
- Advanced Excel functions (XLOOKUP, Pivot Tables, nested formulas)

---

*Data snapshot: 2021 — static dataset for portfolio purposes.*
