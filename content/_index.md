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
            Program Days
        - statistic: "XX%"
          description: |
            Graduation Rate
    design:
      # Section background color (CSS class)
      css_class: "bg-white"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        
  - block: cta-image-paragraph
    id: solutions
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
            text: Learn More
            url: https://nevergiveuptest.netlify.app/blog/
#        - title: Large Community
#          text: Join our large community on Discord - ask questions and get live responses
#          feature_icon: bolt
#          features:
#            - "Dedicated support channel"
#            - "3,000+ users on Discord"
#            - "Share your site and get feedback"
#          # Upload image to `assets/media/` and reference the filename here
#          image: coffee.jpg
#          button:
#            text: Join Discord
#            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      
  - block: features
    id: features
    content:
      title: Our Approach
      text: The NGU Transitional Living program creates a supportive space where individuals with lived experiences (i.e., previously incarcerated) serve as mentors, helping participants navigate challenges related to addiction, antisocial thinking patterns, employment, and prosocial and community reintegration. By offering structured support, the program seeks to empower participants to rebuild their lives and achieve long-term stability.
      items:
        - name: 24/7 Supervision and Accountability
          icon: user-shield
          description: Structured housing with curfews, rules, camera monitoring, and required program participation.
        - name: Stable Housing
          icon: home
          description: Safe, consistent housing throughout the program.
        - name: Support Services
          icon: handshake
          description: Help with IDs, benefits, transportation, clothing, hygiene, and basic needs.
        - name: Employment and Workforce Development
          icon: briefcase
          description: Support with job placement, resumes, and interview skills.
        - name: Therapy and Life Skills Development
          icon: brain
          description: Counseling, sobriety support, financial literacy, and life skills groups.
        - name: Family, Prosocial Peers, and Community Network (Re)Development
          icon: people-roof
          description: Encourages healthy relationships, church, volunteering, and community outings.

  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Hugo Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
        
  - block: cta-card
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
