---
layout: page
title: ""
---
<style>
  .profile-container {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 20px;
  max-width: 1000px;
  margin: 0 auto;
  padding: 20px;
}

.profile-text {
  flex: 2;             /* text gets twice the space */
  font-size: 1.1rem;
  line-height: 1.6;
  min-width: 300px;    /* prevents text from shrinking too much */
}

.profile-photo {
  flex: 1;             /* photo gets half the space of text */
  max-width: 350px;    /* limit max width so it doesn't get too large */
}

.profile-photo img {
  width: 100%;         /* fill the container */
  height: auto;
  border-radius: 8px;
}

@media (max-width: 700px) {
  .profile-container {
    flex-direction: column;
  }

  .profile-photo {
    width: 100%;
    max-width: none;
    margin-top: 20px;
  }
}
</style>

<div class="profile-container">
  <div class="profile-text">
    <p>I am Hoan La, also known as Lana, a PhD candidate in Political Science at Texas Tech University.</p>
    <p>My research lies at the intersection of International Relations, Gender and Politics, Public Administration, and Health. Broadly, I am interested in economic sanctions, armed conflicts, public opinion, gender, state capacity, governance, and health outcomes. One part of my agenda examines how female political representation, public opinion, and governance quality shape foreign policy outcomes, including decisions about war and peace. Another part focuses on how sanctions, conflicts, and administrative capacity influence public health, particularly women's health in developing countries, and how political will and state capacity moderate these effects.</p>
    <p>My dissertation, titled "The Gendered Politics of Sanctions: Women’s Impact, Agency, and Public Opinion", explores the gendered dimensions of international sanctions through three interconnected research questions: 1) How do domestic factors shape the gendered effects of sanctions? 2) Can an increase in female legislators in the target parliament affect sanction termination? 3) Does the gender of leaders in target countries impact public support for the use of sanctions?</p>
    <p>My work uses a combination of experimental, cross-national, and observational data to examine the gendered dynamics of conflict, cooperation, and governance.</p>
  </div>

  <div class="profile-photo">
    <img src="/assets/img/IMG_8447.JPG" alt="Lana photo">
  </div>
</div>
