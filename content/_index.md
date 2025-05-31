---
title: 'Home'
date: 2025-05-30
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Never Give Up Transitional Living
      text: A structured transitional housing program operated under the nonprofit 501(c)(3) organization, Good Turn Labor, to support formerly incarcerated individuals as they reintegrate into the community.
      primary_action:
        text: Support Second Chances
        url: https://www.convergepay.com/hosted-payments/?ssl_txn_auth_token=hZimVnstSY2Sr9jySrL%2FjAAAAZZEoSpl#!/payment-method
        icon: rocket-launch
        class: "btn-yellow"
    design:
      css_class: "hero-text"
      background:
        color: "#003366"  # dark blue background for contrast
        image:
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
      spacing:
        padding: [0, 0, 0, 0]

  - block: stats
    content:
      items:
        - statistic: "16"
          description: |
            Men Admitted     
            Since March 2025
        - statistic: "84"
          description: |
            Days of Programming
        - statistic: "XX%"
          description: |
            Graduation Rate
    design:
      css_class: "bg-lightblue section-padding"

  - block: markdown
    id: program
    content:
      title: About
      text: |
        <br>
        <c style="color:#4A4A4A; font-size:1.125rem;">The Never Give Up Transitional Living program serves men released from prison who: (a) are approved for community supervision or parole, (b) are motivated to participate in structured reentry support, and (c) have applied to the program and completed a phone interview and background review.

        The overarching goal of the program is to reduce recidivism and promote successful reintegration by fostering personal accountability, community support, and access to essential resources.</c>
    design:
      css_class: "bg-white section-padding"
  
  - block: cta-image-paragraph
    content:
      items:
        - title: What Makes **Never Give Up Transitional Living** Unique?
          text: Rooted in experience. Driven by hope.
          feature_icon: bolt
          features:
            - "**We don't give up.** No matter your past, we believe in your future."
            - "**Built for real change.** Helping people rebuild lives -- not just get by."
            - "**We've been there.** Most of our team has been incarcerated—and made it out stronger."
          image: groupphoto1.jpeg
          button:
            text: Meet the Team
            url: https://nevergiveuptest.netlify.app/#ourteam
            class: "btn-yellow"
        - title: The NGU Approach
          text: Never Give Up creates a supportive space where individuals with lived experiences (i.e., previously incarcerated) serve as mentors, helping participants navigate challenges related to addiction, antisocial thinking patterns, employment, and prosocial and community reintegration. By offering structured support, the program seeks to empower participants to rebuild their lives and achieve long-term stability.
          feature_icon: bolt
          features:
            - "24/7 supervision and accountability"
            - "Stable housing"
            - "Support services"
            - "Employment and workforce development"
            - "Therapy and life skills development"
            - "Family, prosocial peers, and community network (re)development"
          image: GroupPhoto_2.jpg
    design:
      css_class: "bg-lightgray section-padding"

  # ...other blocks with alternating bg classes, e.g. bg-white, bg-lightblue, bg-lightgray

---
