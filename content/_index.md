---
title: 'Home'
date: 2025-05-30
type: landing

design:
  # Default section spacing
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
      secondary_action:
        text: Learn About Our Team
        url: https://docs.hugoblox.com
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
            
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
      # Section background color (CSS class)
      css_class: "bg-white"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        
  - block: markdown
    id: program
    content:
      title: |
        About
      text: |
        <br>
        <c>The Never Give Up Transitional Living program serves men released from prison who: (a) are approved for community supervision or parole, (b) are motivated to participate in structured reentry support, and (c) have applied to the program and completed a phone interview and background review.
        
        The overarching goal of the program is to reduce recidivism and promote successful reintegration by fostering personal accountability, community support, and access to essential resources.</c>
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"        
  
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
          # Upload image to `assets/media/` and reference the filename here
          image: groupphoto1.jpeg
          button:
            text: Meet the Team
            url: https://nevergiveuptest.netlify.app/#ourteam
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
          # Upload image to `assets/media/` and reference the filename here
          image: GroupPhoto_2.jpg
          button:
            text: Learn More
            url: https://nevergiveuptest.netlify.app/materials/
#        - title: Community (Re)Integration
#          text: Our program is supported by a broad network that includes community organizations, employers, and strong partnerships with the criminal justice system.
#          feature_icon: bolt
#          features:
#            - "Connections to local community organizations and universities"
#            - "Partnerships with employers offering job opportunities"
#            - "Collaborative support from parole officers"
#          # Upload image to `assets/media/` and reference the filename here
#          image: HockeyPhoto.jpeg
#          button:
#            text: Join Discord
#            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-white"
      
  - block: features
    content:
      title: NGU Programming Opportunities
      text: 
      items:
        - name: Group Dialectical Behavior Therapy (DBT)
          icon: light-bulb
          description: Evidence-based group therapy focused on emotional regulation, distress tolerance, and interpersonal skills.
        - name: Intensive Outpatient Programming (IOP)
          icon: chat-bubble-oval-left-ellipsis
          description: Structured clinical treatment that includes group sessions, relapse prevention, and coping strategies.
        - name: Individual Counseling
          icon: heart
          description: One-on-one sessions with licensed counselors to address trauma, mental health, substance use, and personal growth.
        - name: Alcoholics Anonymous and Narcotics Anonymous
          icon: star
          description: Peer-led recovery group attendance offering 12-step support and a strong sober community.
        - name: Financial Literacy Classes
          icon: currency-dollar
          description: Practical education on budgeting, saving, credit, and building long-term financial stability.
        - name: Faith-Based Support
          icon: user-group
          description: Spirtual mentorship and participation in faith-based community activities.
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"        

  - block: cards
    id: documentation
    content:
      title: Program Documentation
      text: Access our core materials to better understand our policies, procedures, and services.
      items:
        - title: Participant Handbook
          content: Rules, expectations, and resources for participants entering the program.
          icon: document-text
          image: pdf-icon.png
          url: /docs/participant-handbook.pdf
        - title: Program Overview
          content: Summary of services, eligibility criteria, and program goals.
          icon: document-text
          image: pdf-icon.png
          url: /docs/program-overview.pdf
        - title: Staff Code of Conduct
          content: Ethical standards and behavioral expectations for NGU staff members.
          icon: document-text
          image: pdf-icon.png
          url: /docs/staff-code-of-conduct.pdf
    design:
      css_class: "bg-white"

#  - block: testimonials
#    content:
#      title: "Testimonials"
#      text: ""
#      items:
#        - name: "Hugo Smith"
#          role: "Marketing Executive at X"
#          # Upload image to `assets/media/` and reference the filename here
#          image: "testimonial-1.jpg"
#          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
#    design:
#      spacing:
#        # Reduce bottom spacing so the testimonial appears vertically centered between sections
#        padding: ["6rem", 0, 0, 0]
        
  - block: cta-card
    id: donate
    content:
      title: Help us Change Lives
      text: Donate to Never Give Up through Good Turn Labor, LLC
      button:
        text: Support Second Chances
        url: https://www.convergepay.com/hosted-payments/?ssl_txn_auth_token=hZimVnstSY2Sr9jySrL%2FjAAAAZZEoSpl#!/payment-method
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
