---
layout: page
title: ""
---
</style>
.profile-container {
    display: flex;
    align-items: stretch;       /* Stretch children to same height */
    justify-content: space-between;
    gap: 20px;
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
  }

  .profile-text {
    flex: 2;                    /* Text takes 2/3 space */
    font-size: 1.1rem;
    line-height: 1.6;
    min-width: 300px;
  }

  .profile-photo {
    flex: 1;                    /* Photo takes 1/3 space */
    max-width: 350px;
    height: auto;
  }

  .profile-photo img {
    width: 100%;
    height: 100%;               /* Stretch to fill parent height */
    object-fit: cover;          /* Crop to fill without distortion */
    border-radius: 8px;
  }

  @media (max-width: 700px) {
    .profile-container {
      flex-direction: column;
      align-items: flex-start;
    }

    .profile-photo {
      width: 100%;
      max-width: none;
      margin-top: 20px;
      height: auto;
    }

    .profile-photo img {
      height: auto;
      object-fit: contain;
    }
  }
</style>

<div class="profile-container">
  <div class="profile-text">
    <p>I am Hoan La, also known as Lana, a PhD candidate in Political Science at Texas Tech University.</p>
    <p>My research lies at the intersection of International Relations, Gender and Politics, Public Administration, and Health. Broadly, I am interested in economic sanctions, armed conflicts, public opinion, gender, state capacity, governance, and health outcomes. One part of my agenda examines how female political representation, public opinion, and governance quality shape foreign policy outcomes, including decisions about war and peace. Another part focuses on how sanctions, conflicts, and administrative capacity influence public health, particularly women's health in developing countries, and how political will and state capacity moderate these effects.</p>
  </div>

  <div class="profile-photo">
    <img src="/assets/img/IMG_8447.JPG" alt="Lana photo">
  </div>
</div>
