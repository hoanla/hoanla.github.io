---
layout: page
title: ""
---

<style>
  .profile-container {
    display: flex;
    align-items: flex-start;
    gap: 20px;
  }

  .profile-text {
    flex: 1;
    font-size: 1.1rem;
    line-height: 1.5;
  }

  .profile-photo {
    flex: 0 0 250px;
  }

  .profile-photo img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
  }

  @media (max-width: 600px) {
    .profile-container {
      flex-direction: column;
    }

    .profile-photo {
      flex: none;
      margin-top: 15px;
      width: 100%;
    }
  }
</style>

<div class="profile-container">
  <div class="profile-text">
    <p>I am Lana, a PhD candidate in Political Science at Texas Tech University.</p>
    <p>My research focuses on economic sanctions, gender, and international political behavior. I study how female political representation and public opinion shape foreign policy decision-making in democracies.</p>
    <p>My work uses a combination of experimental, cross-national, and observational data to examine the gendered dynamics of conflict and cooperation.</p>
  </div>

  <div class="profile-photo">
    <img src="/assets/img/IMG_8447.JPG" alt="Lana photo">
  </div>
</div>
