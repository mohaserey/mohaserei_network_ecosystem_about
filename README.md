# mohaserei_network_ecosystem_about
Mohaserei System Network (MSN) — Ecosystem Overview

Welcome to the Mohaserei System Network (MSN) ecosystem documentation. Mohaserei is a modular digital platform and community economic network designed to support regional onboarding, member coordination, economic scoring, and local commerce across Cambodia.

Ecosystem Architecture

The Mohaserei network is organized into interconnected modules that share identity, regional administrative metadata, and economic rules:

Dashboard Module

Central operational overview for network activity, regional distribution, and system metrics.

Registration & Regional Hierarchy Module

Captures member onboarding data mapped to Cambodia's administrative divisions (Provinces/Capital, Municipalities/Districts, and Communes/Sangkats).

Uses standardized JavaScript JSON hierarchy datasets for deterministic validation and regional filtering.

Member Directory Module

Provides searchable and filterable member profiles organized by region, participation status, and network role.

Economy & UES Engine

Computes and tracks economic indicators including the Universal Economic Score (UES), Human Contribution Value (HCV) formulas, profit-sharing rules, and MSN Coin valuation mechanics.

MSN Marketplace

Serves as the Layer 2 economic transaction and merchant network enabling local trade, merchant listings, and value circulation within the Mohaserei ecosystem.

Regional Data & Localization

Geographic Coverage: Structured lookup hierarchies covering Cambodia's capital and provinces (including Phnom Penh, Siem Reap, Battambang, Kandal, Kampong Chhnang, Kampong Speu, Kampong Thom, Kampot, Kampong Cham, Koh Kong, Kratie, Mondulkiri, Oddar Meanchey, Pursat, Preah Vihear, Preah Sihanouk, Prey Veng, Ratanakiri, Banteay Meanchey, Stung Treng, Svay Rieng, Takeo, Tboung Khmum, Kep, and Pailin).

Naming Standard: Always use the exact brand spelling Mohaserei across repositories, modules, documentation, and datasets.

Repository Structure (Suggested)

mohaserei-network/
├── dashboard/
├── registration/
│   └── data/
│       └── cambodia-divisions.js
├── member-directory/
├── economy-ues-engine/
├── marketplace/
└── mohaserei_network_ecosystem_about/
    └── README.md


Governance & Contribution Guidelines

Keep all module interfaces well-documented so front-end views, regional lookup datasets, and economic calculation rules stay in sync.

Verify administrative division names (Khmer script and hierarchy levels) before merging updates into the registration dataset.

Maintain consistent terminology for Mohaserei, UES, HCV, and MSN Coin across all ecosystem files.
