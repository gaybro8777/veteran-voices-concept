---
permalink: /dashboard/
layout: page
title: Example Dashboard
---

<div class="dashboard-header">
  <h1>Example Dashboard</h1>
  <div class="dashboard-filters">
    <select>
      <option>Last 24 Hours</option>
      <option>Last 7 Days</option>
      <option>Last 14 Days</option>
      <option>Last 30 Days</option>
    </select>
  </div>
</div>
<div class="dashboard-row clearfix">
  <div class="card">
    <div class="card-heading">Top & Emerging Conversations</div>
    <ul class="usa-unstyled-list phrase-list">
      <li>
        <div class="phrase-heading">
          “NY Office of Patient Advocacy.”
        </div>
        <div class="phrase-sentiment positive">
          <strong>72%</strong> Positive
        </div>
      </li>
      <li>
        <div class="phrase-heading">
          “American Corporate Partnership California.”
        </div>
        <div class="phrase-sentiment positive">
          <strong>58%</strong> Positive
        </div>
      </li>
      <li>
        <div class="phrase-heading">
          “NY VA”
        </div>
        <div class="phrase-sentiment negative">
          <strong>53%</strong> Negative
        </div>
      </li>
      <li>
        <div class="phrase-heading">
          “Card benefits”
        </div>
        <div class="phrase-sentiment positive">
          <strong>54%</strong> Positive
        </div>
      </li>
      <li>
        <div class="phrase-heading">
          “Logan airport USO.”
        </div>
        <div class="phrase-sentiment positive">
          <strong>68%</strong> Positive
        </div>
      </li>
    </ul>
  </div>
</div>
<div class="dashboard-row clearfix">
  <div class="usa-width-one-half">
    <div class="card">
      <div class="card-heading">Projected News Trajectory</div>
      <img src="{{ site.baseurl }}/assets/img/figures/dashboard-trajectory.png" alt="News Trajectory Visualization">
    </div>
  </div>
  <div class="usa-width-one-half">
    <div class="card">
      <div class="card-heading">Positive Sentiment by Platform</div>
      <img src="{{ site.baseurl }}/assets/img/figures/dashboard-sentiment.png" alt="Positive Sentiment by Platform">
    </div>
  </div>
</div>