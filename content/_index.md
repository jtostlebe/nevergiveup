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
      text: A structured transitional housing program in Omaha, Nebraska operated under the nonprofit 501(c)(3) organization, Good Turn Labor, to support formerly incarcerated individuals as they reintegrate into the community.
      primary_action:
        text: Support The Program
        url: https://www.convergepay.com/hosted-payments/?ssl_txn_auth_token=hZimVnstSY2Sr9jySrL%2FjAAAAZZEoSpl#!/payment-method
        icon: rocket-launch
#        style: "background-color: #FACC15; color: #1F2937; padding: 0.5rem 1rem; border-radius: 0.375rem; font-weight: 600;"
#      secondary_action:
#        text: Learn About Our Team
#        url: https://docs.hugoblox.com
    design:
      css_class: "dark text-white"
      background:
        color: "#0E2240"  # Navy Blue Background
        image:
          # Add your image background to `assets/media/`.
          filename: bg-waves.svg
          filters:
            brightness: 0.5
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
            
  - block: stats
    content:
      items:
        - statistic: "13"
          description: |
            Men Admitted     
            Since March 2025
        - statistic: "84"
          description: |
            Days of Programming
        - statistic: "--%"
          description: |
            Graduation Rate     
            (Data Not Yet Available) 
    design:
      css_class: "bg-white text-[#003366]"      
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        
  - block: markdown
    id: program
    content:
      title: >
        About the Program
      text: >
        <img src="/media/logo.png" alt="NGU Logo" style="max-height: 200px; display: block; margin: 0 auto 1rem auto;">
        
        <span style="color:#4D3B2F; font-size:1.125rem; text-align: center; display: block;">
        Never Give Up (NGU) Transitional Living serves <strong>men released from prison</strong> in Nebraska who:
        <br>
        (a) are approved for community supervision or parole,<br>
        (b) are motivated to participate in structured reentry support, and<br>
        (c) have applied to the program and completed a phone interview and background review.
        <br><br>
        The <strong>overarching goal</strong> of the program is to reduce recidivism and promote successful reintegration by fostering personal accountability, community support, and access to essential resources.</span>
    
    design:
      css_class: bg-gray-100
  
  - block: cta-image-paragraph
    content:
      items:
        - title: '<span style="color:#141436;">The NGU Approach</span>'
          text: '<span style="color:#4d4d4d;">Never Give Up Transitional Living creates a supportive space where individuals with lived experiences (i.e., previously incarcerated) serve as mentors, helping participants navigate challenges related to addiction, antisocial thinking patterns, employment, and prosocial and community reintegration.<br><br>By offering structured support, the program seeks to empower participants to rebuild their lives and achieve long-term stability.<br><br>Core elements of the program include:</span>'
          feature_icon: bolt
          features:
            - '<span style="color:#36454F;">24/7 supervision and accountability</span>'
            - '<span style="color:#36454F;">Stable housing</span>'
            - '<span style="color:#36454F;">Commitment to sobriety and recovery support</span>'
            - '<span style="color:#36454F;">Employment and workforce development</span>'
            - '<span style="color:#36454F;">Therapy and life skills development</span>'
            - '<span style="color:#36454F;">Family, prosocial peers, and community network (re)development</span>'
          image: GroupPhoto_2.jpg
          button:
            text: Program Overview (PDF)
            url: /docs/NGUProgramDescription.pdf
#        - title: Community (Re)Integration
#          text: Our program is supported by a broad network that includes community organizations, employers, and strong partnerships with the criminal justice system.
#          feature_icon: bolt
#          features:
#            - "Connections to local community organizations and universities"
#            - "Partnerships with employers offering job opportunities"
#            - "Collaborative support from parole officers"
#          image: HockeyPhoto.jpeg
#          button:
#            text: Join Discord
#            url: https://discord.gg/z8wNYzb
    design:
      css_class: "bg-[#FFFFFF]"
      
  - block: features
    content:
      title: NGU Programming + Services
      text: 
      items:
        - name: Dialectical Behavior Therapy (DBT)
          icon: light-bulb
          description: Evidence-based group therapy focused on emotional regulation, distress tolerance, and interpersonal skills.
        - name: Intensive Outpatient Programming (IOP)
          icon: chat-bubble-oval-left-ellipsis
          description: Structured clinical treatment that includes group sessions, relapse prevention, and coping strategies.
        - name: Individual Counseling
          icon: user
          description: One-on-one sessions with licensed counselors to address trauma, mental health, substance use, and personal growth.
        - name: Alcoholics Anonymous (AA) and Narcotics Anonymous (NA)
          icon: star
          description: Peer-led recovery group attendance offering 12-step support and a strong sober community.
        - name: Financial Literacy Classes
          icon: currency-dollar
          description: Practical education on budgeting, saving, credit, and building long-term financial stability.
        - name: Faith-Based Support
          icon: heart
          description: Spiritual mentorship and participation in faith-based community activities.
        - name: Housing & Basic Needs
          icon: home
          description: Safe and stable housing for the program duration, including provision of initial clothing, food, transportation, and cellphones.
        - name: Essential Documents Assistance
          icon: identification
          description: Support with obtaining or replacing ID, Social Security cards, EBT, and Medicaid enrollment if needed.
        - name: Community & Family Engagement
          icon: users
          description: Organized social outings and family visitation days to help participants rebuild connections with loved ones and the community.
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"        

  - block: cta-image-paragraph
    content:
      items:
        - title: '<span style="color:#141436;">What Makes NGU Unique?</span>'
          text: '<span style="color:#4d4d4d;">Rooted in experience. Driven by hope.</span>'
          feature_icon: bolt
          features:
            - '<span style="color:#36454F;"><strong>Out-of-the-box.</strong> Innovative methods tailored for lasting impact.</span>'
            - '<span style="color:#36454F;"><strong>We don''t give up.</strong> No matter your past, we believe in your future.</span>'
            - '<span style="color:#36454F;"><strong>We''ve been there.</strong> Our staff have done time, and changed their lives.</span>'
            - '<span style="color:#36454F;"><strong>Built for real change.</strong> Helping people rebuild lives -- not just get by.</span>'
          image: groupphoto1.jpeg
          button:
            text: Meet the NGU Team
            url: /people
            style: "background-color: #FECA1B; color: #0E2240; font-weight: 700; display: block; margin: 0 auto;"

#  - block: markdown
#    id: documentation
#    content:
#      title: Program Documentation
#      text: |
#        Access our core materials to better understand our policies, procedures, and services:
#        
#        - [**Program Overview** (PDF)](/docs/NGUProgramDescription.pdf): Summary of program goals, logic model, eligibility criteria, participant rules and expectations, and services.
#        - [**Staff Descriptions** (PDF)](/docs/NGUStaffRoleDescriptions.pdf): Employee roles, job descriptions, and qualification expectations.
#        - [**Never Give Up Program Flyer** (PDF)](/docs/NGUFlyer.pdf): Print-ready handout describing our services.
#    design:
#      css_class: "bg-white"

  - block: cta-card
    id: donate
    content:
      title: Help us Change Lives
      text: Donate to Never Give Up through the 501(c)(3) organization, Good Turn Labor, LLC
      button:
        text: Support Our Mission
        url: https://www.convergepay.com/hosted-payments/?ssl_txn_auth_token=hZimVnstSY2Sr9jySrL%2FjAAAAZZEoSpl#!/payment-method
    design:
      css_class: "bg-gray-100"
      card:
        css_class: "bg-primary-700"
        css_style: ""

  - block: features
    id: contact
    content:
      title: Contact Us
      items:
        - name: Program Director Shane Reilly, M.S.
          icon: phone
          description: "📞 (402) 359-7404"
        - name: Email Us
          icon: envelope
          description: "[ngutlomaha@gmail.com](mailto:ngutlomaha@gmail.com)"
        - name: Location
          icon: map-pin
          description: |
            Omaha, Nebraska
            
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3067.8843491753914!2d-95.9345031846238!3d41.25653617927001!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x87938e6f1b8f0b8f%3A0xd53bfbb7c5304466!2sOmaha%2C%20NE!5e0!3m2!1sen!2sus!4v1695970800000!5m2!1sen!2sus"
              width="100%"
              height="200"
              style="border:0;"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
        - name: Want to help us spread the word?
          icon: chat-bubble-oval-left
          description: |
            [Click **HERE** to download our flyer.](/docs/NGUFlyer.pdf)

            Share it with someone who might benefit or want to support us!
    design:
      css_class: "bg-white features-contact-items"
      
#  - block: testimonials
#    content:
#      title: "Testimonials"
#      text: ""
#      items:
#        - name: "Hugo Smith"
#          role: "Marketing Executive at X"
#          image: "testimonial-1.jpg"
#          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
#    design:
#      spacing:
#        padding: ["6rem", 0, 0, 0]
        
---
