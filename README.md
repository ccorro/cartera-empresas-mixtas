# Tablero Financiero Empresas Mixtas

## Overview

Financial dashboard for the analysis and valuation of Chile's mixed-capital companies portfolio (state and private co-owned enterprises). This interactive dashboard provides comprehensive financial metrics, risk analysis, and valuation models.

## Features

### Key Indicators (KPIs)
- **Enterprise Value**: $9,262.9M total portfolio value
- **Consolidated Revenue**: $3,709.4M
- **EBITDA**: $1,107.7M (35.13% margin average)
- **Annual Dividends to State**: $166.0M (49% ownership)

### Companies Included

| Company | Sector | Revenue | EBITDA | EV | State % | VP Position |
|---------|--------|---------|--------|-----|---------|------------|
| CWP | Telecom | $783.5M | $275.9M | $2,005.6M | 49% | $374.1M |
| AES Panamá | Gen. Eléctrica | $450.0M | $185.0M | $1,239.9M | 49% | $607.6M |
| EDEMET | Dist. Eléctrica | $910.8M | $176.2M | $1,321.7M | 49% | Affected |
| ENEL Fortuna | Gen. Eléctrica | $210.9M | $129.2M | $903.0M | 49% | $442.5M |
| ENSA | Dist. Eléctrica | $650.0M | $116.0M | $870.0M | 49% | Affected |
| PPC | Puertos | $363.1M | $119.4M | $1,705.5M | 10% | $170.6M |
| EDECHI | Dist. Eléctrica | $215.5M | $53.3M | $399.8M | 49% | $195.9M |
| PTP | Energía | $114.8M | $43.8M | $754.9M | 49% | $369.9M |
| ESEPSA | Gen. Eléctrica | $11.7M | $8.9M | $62.5M | 49% | $30.6M |

### Portfolio Composition
- **Electrical Distribution**: 28% ($2,594.5M)
- **Power Generation**: 24% ($2,223.2M)
- **Telecom**: 22% ($2,039.4M)
- **Ports**: 18% ($1,667.8M)
- **Energy**: 8% ($738.0M)

### Key Metrics

#### Performance Ratios
- **Collateral Yield**: 7.58% (Optimal)
- **Projected Div. Growth**: +3.00% (Stable)
- **Average EBITDA Margin**: 35.13% (On Target)
- **Implicit Average Multiple**: 8.36x (Consistent)
- **Average Annual Dividend Ticket**: $18.44M (Healthy)

#### Risk & Concentration
- **Electrical Block Concentration**: 51.79% (High Risk)
- **Max Asset Concentration (AES)**: 27.73% (Under Review)
- **Interest Rate Risk**: SOFR+300 (Subject to Market)
- **Projected Debt Coverage**: 1.13x (Stable)
- **Net Collateral DCF (9%/20y)**: $1,504.0M (Viable)

### Risk Matrix

| Category | Level | Impact | Mitigation |
|----------|-------|--------|-----------|
| Regulatory & Legal | **HIGH** | Tariff revisions, Law 48/2013 reforms | Formal opinions from Comptroller & Audit |
| Market & Valuation | **MEDIUM-HIGH** | SOFR sensitivity, EDEMET/ENSA debt | Swap contracts, bounded spreads |
| Operational & Dividends | **MEDIUM** | Hydrological regime dependency | Mandatory DSRA 1.5x coverage |
| Holding Execution | **MEDIUM-HIGH** | Bureaucracy, market volatility | Parallel investment banking support |

### Interactive Features

#### DCF Sensitivity Analysis
- Adjustable discount rate (6% - 12%)
- Dynamic valuation calculations
- Multi-year horizons (10, 15, 20, 25 years)
- Real-time updates

#### Interactive Charts
- **Waterfall Chart**: Portfolio composition by sector
- **EBITDA Bar Chart**: Company-by-company performance
- **DCF Curve**: Valuation sensitivity analysis
- Hover tooltips for detailed information

## Proposed Holding Structure

```
State of Chile (Ministry of Finance)
         ↓
Holding of Mixed Enterprises SpA
         ↓
    9 Companies
```

### Centralized Dividends
- ENSA (49%): $36.3M
- ENEL Fortuna (49%): $36.0M
- AES (49%): $26.0M
- CWP (49%): $18.8M
- EDEMET (49%): $18.2M
- Others: $30.7M
- **TOTAL: $166.0M USD/year**

### Financing Channels
- **Channel A: Bonds** — Up to $1,328M at SOFR + 150-250 bps
- **Channel B: Syndicated Credit** — Up to $996M at SOFR + 200-300 bps

## Usage

1. Open `index.html` in a web browser
2. Interact with charts and data tables
3. Adjust DCF discount rate slider to see valuation sensitivity
4. Hover over chart elements for detailed information

## Technology Stack

- **HTML5** — Semantic markup
- **Tailwind CSS** — Responsive styling
- **Canvas API** — Interactive chart rendering
- **Vanilla JavaScript** — No dependencies (except Tailwind CDN)

## Key Conclusions

The Chilean state's mixed-company portfolio represents a significant asset worth $9.3B in enterprise value, generating $166M in annual dividends (9% yield). The proposed holding structure enables centralized management, optimized financial restructuring through debt issuance, and maximized fiscal returns. Primary risks concentrate in tariff regulation (51.79% electrical exposure), interest rate volatility, and hydrological dependency. Execution recommended with parallel international investment banking support.

## Confidentiality

**CONFIDENTIAL — RESTRICTED USE**

Prepared for: MEF - DICRE (Ministry of Finance - Directorate of State Companies)

Prepared by: César Corro Arjona

Period: 2024-2025

---

*This dashboard was created from HTML code without Canva dependencies for maximum portability and technical control.*
