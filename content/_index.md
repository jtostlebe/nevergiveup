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
        style: "background-color: #FFCC00; color: #003366; padding: 0.5rem 1rem; border-radius: 0.375rem; font-weight: 600;"
    design:
      css_class: "text-white"
      background:
        color: "#003366"  # Dark Blue Background
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
      css_class: "bg-lightblue text-darkblue"      
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        
  - block: markdown
    id: program
    content:
      title: About
      text: |
        <br>
        <p style="color:#4A4A4A; font-size:1.125rem;">The Never Give Up Transitional Living program serves men released from prison who: (a) are approved for community supervision or parole, (b) are motivated to participate in structured reentry support, and (c) have applied to the program and completed a phone interview and background review.
        
        The overarching goal of the program is to reduce recidivism and promote successful reintegration by fostering personal accountability, community support, and access to essential resources.</p>
    design:
      css_class: "bg-white"        
  
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
            style: "background-color: #FFCC00; color: #003366; font-weight: 700;"
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
      css_class: "bg-white"
      
  - block: features
    content:
      title: NGU Programming Opportunities
      text: 
      items:
        - name: Dialectical Behavior Therapy (DBT)
          icon: light-bulb
          description: Evidence-based group therapy focused on emotional regulation, distress tolerance, and interpersonal skills.
        - name: Intensive Outpatient Programming (IOP)
          icon: chat-bubble-oval-left-ellipsis
          description: Structured clinical treatment that includes group sessions, relapse prevention, and coping strategies.
        - name: Individual Counseling
          icon: heart
          description: One-on-one sessions with licensed counselors to address trauma, mental health, substance use, and personal growth.
        - name: Alcoholics Anonymous (AA) and Narcotics Anonymous (NA)
          icon: star
          description: Peer-led recovery group attendance offering 12-step support and a strong sober community.
        - name: Financial Literacy Classes
          icon: currency-dollar
          description: Practical education on budgeting, saving, credit, and building long-term financial stability.
        - name: Faith-Based Support
          icon: user-group
          description: Spiritual mentorship and participation in faith-based community activities.
    design:
      css_class: "bg-lighttan"        

  - block: markdown
    id: documentation
    content:
      title: Program Documentation
      text: |
        Access our core materials to better understand our policies, procedures, and services:
        
        - [**Program Overview** (PDF)](/docs/NGUProgramDescription.pdf): Summary of program goals, logic model, eligibility criteria, participant rules and expectations, and services.
        - [**Staff Descriptions** (PDF)](/docs/NGUStaffRoleDescriptions.pdf): Employee roles, job descriptions, and qualification expectations.
        - [**Never Give Up Program Flyer** (PDF)](/docs/NGUFlyer.pdf): Print-ready handout describing our services.
    design:
      css_class: "bg-white"

  - block: cta-card
    id: donate
    content:
      title: Help us Change Lives
      text: Donate to Never Give Up through Good Turn Labor, LLC
      button:
        text: Support Our Mission
        url: https://www.convergepay.com/hosted-payments/?ssl_txn_auth_token=hZimVnstSY2Sr9jySrL%2FjAAAAZZEoSpl#!/payment-method
        style: "background-color: #FFCC00; color: #003366; font-weight: 700;"
    design:
      css_class: "bg-lightblue"
      card:
        css_class: "bg-mediumblue"
        css_style: ""

  - block: features
    id: contact
    content:
      title: Contact Us
      items:
        - name: Program Director Shane Reilly, M.S.
          icon: phone
          description: 📞 (402) 359-7404  
        - name: 
          icon: user
          description: |
            ![](Shane.jpg)
        - name: Email Us
          icon: envelope
          description: '[ngutlomaha@gmail.com](mailto:ngutlomaha@gmail.com)'
    design:
      css_class: "bg-lighttan"
      
---
