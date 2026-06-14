---
layout: single
title: "Toys"
permalink: /toys/
author_profile: true
---

Some interactive toys & simulations I built for fun.

## Matching Theory: The Cost of Early Offers

An interactive Monte Carlo simulation exploring how "rushing" (提前锁定) in bilateral matching markets harms overall efficiency. 
Simulates 100 candidates × 25 firms under Gale-Shapley deferred acceptance, comparing perfect competition with early-offer scenarios.

[Open Simulation →](/toys/matching-rush/)

<style>
.toy-card {
  display: flex;
  gap: 20px;
  align-items: flex-start;
  padding: 16px 20px;
  border: 1px solid var(--global-border-color, #ddd);
  border-radius: 8px;
  margin-bottom: 16px;
  transition: border-color 0.2s;
  text-decoration: none;
  color: inherit;
}
.toy-card:hover {
  border-color: var(--global-theme-color, #0077b6);
}
.toy-card-icon {
  font-size: 32px;
  flex-shrink: 0;
  width: 48px;
  text-align: center;
}
.toy-card-body h3 {
  margin: 0 0 4px 0;
  font-size: 16px;
}
.toy-card-body p {
  margin: 0;
  font-size: 14px;
  color: #666;
}
.toy-card-badge {
  display: inline-block;
  font-size: 11px;
  padding: 2px 8px;
  border-radius: 10px;
  background: #e8f4fd;
  color: #0077b6;
  margin-top: 6px;
}
</style>

<a href="/toys/matching-rush/" class="toy-card">
  <div class="toy-card-icon">📊</div>
  <div class="toy-card-body">
    <h3>Matching Rush Simulation</h3>
    <p>Interactive Monte Carlo simulation of bilateral matching with early offers. 100 candidates × 25 firms.</p>
    <span class="toy-card-badge">Economics</span>
    <span class="toy-card-badge">Matching Theory</span>
    <span class="toy-card-badge">Monte Carlo</span>
  </div>
</a>
