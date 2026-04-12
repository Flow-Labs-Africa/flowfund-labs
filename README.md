# 🌊 FlowFund Protocol

**FlowFund Protocol** is a decentralized, real-time funding infrastructure built on **Stellar + Drips Wave**, enabling continuous micro-streaming of funds to projects, creators, and communities.

> 💡 Rethinking funding: from one-time grants → continuous capital flow

---

## 🚀 Overview

FlowFund Protocol introduces a new financial primitive: **Streaming Funding**.

Instead of static, one-time disbursements, funds are:
- Distributed continuously (per second/minute)
- Dynamically adjusted based on community signals
- Fully transparent and on-chain

This unlocks **sustainable, merit-based funding** for builders globally—starting with Africa.

---

## 🌍 Problem

Traditional funding systems suffer from:
- ❌ One-time grants (unsustainable)
- ❌ Lack of transparency
- ❌ Centralized decision-making
- ❌ Limited access for grassroots innovators

---

## 💡 Solution

FlowFund enables:

### 💸 Continuous Funding Streams
Users stream funds to projects in real-time via Drips Wave.

### 🗳️ Community-Driven Allocation
Funding adjusts based on:
- Votes
- Engagement
- Project activity

### 📊 Impact-Based Distribution
Projects earn more as they:
- Deliver milestones
- Gain traction
- Build trust

### 🔁 Real-Time Control
Supporters can:
- Pause funding
- Redirect streams
- Adjust contributions instantly

---

## 🧱 Monorepo Structure

```bash
flowfund-protocol/
├── apps/
│   ├── web/                # React frontend (user dashboard)
│   ├── api/                # NestJS backend (core services)
│
├── packages/
│   ├── ui/                 # Shared UI components (design system)
│   ├── sdk/                # Stellar + Drips integration SDK
│
├── contracts/
│   ├── soroban/            # Smart contracts (funding logic)
│
├── infra/
│   ├── docker/             # Containerization configs
│   ├── scripts/            # Deployment & automation scripts
│
├── docs/                   # Technical documentation
├── .github/                # CI/CD workflows
└── package.json            # Workspace root config
